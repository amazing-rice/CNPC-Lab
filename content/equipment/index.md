---
title: 实验平台与技术能力
date: 2024-11-25
type: landing

sections:
  # ============================================================
  # 1. 顶部横幅 (保持不变)
  # ============================================================
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div class="text-center text-white d-flex align-items-center justify-content-center" 
             style="background-image: url('/media/equipment/device01.jpg'); background-size: cover; background-position: center; min-height: 350px; border-radius: 8px; position: relative; overflow: hidden;">
          <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.6);"></div>
          <div style="position: relative; z-index: 2; padding: 20px;">
            <h1 style="font-size: 2.5rem; font-weight: bold; color: #fff;">地震物理模型实验室</h1>
            <p style="font-size: 1.2rem; opacity: 0.9; color: #ddd; margin-top: 10px;">
              多尺度物理模拟 · 复杂介质波场研究 · 智能化数据采集
            </p>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '40px', '0']

  # ============================================================
  # 2. 核心技术装备 (8个) - 已修改为悬浮放大
  # ============================================================
  - block: markdown
    content:
      title: 核心技术装备
      subtitle: Advanced Equipment
      text: |
        <style>
          /* 图片基础样式 */
          .zoom-img {
            transition: all 0.3s ease-out; /* 平滑过渡所有属性 */
            display: block;
            width: 100%;
            height: 100%;
            position: relative; /* 为 z-index 做准备 */
            border-radius: 4px; /* 默认轻微圆角 */
          }

          /* 鼠标悬停时的样式 - 关键部分 */
          .zoom-img:hover {
            transform: scale(1.4); /* 放大1.4倍 (1.5倍对于悬浮来说可能有点太大了，1.4视觉更佳) */
            z-index: 999; /* 【核心】极大提高层级，确保浮在最上面 */
            box-shadow: 0 15px 30px rgba(0,0,0,0.3); /* 添加深度阴影，制造悬浮感 */
            border-radius: 6px; /* 放大时圆角稍微明显点 */
          }
          
          /* 确保父级容器不会裁剪溢出的图片 */
          .card, .d-flex, .img-wrapper-reset {
              overflow: visible !important;
          }
        </style>

        <p class="text-muted text-center mb-5">实验室拥有多套自主研发及引进的国际先进物理模拟和测试系统。</p>
        <div class="container-fluid">
          <div class="row">
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_elastic.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">动静态弹性测试</h6></div>
              </div>
            </div>
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_bechlab.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">Bechlab 系统</h6></div>
              </div>
            </div>
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_laser.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">超声激光测试</h6></div>
              </div>
            </div>
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_optical.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">光学成像系统</h6></div>
              </div>
            </div>
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_press.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">四轴热压设备</h6></div>
              </div>
            </div>
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_3d_acq.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">三维高精度采集</h6></div>
              </div>
            </div>
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_air_float.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">气浮模拟系统</h6></div>
              </div>
            </div>
            <div class="col-6 col-md-3 mb-4 text-center">
              <div class="card h-100 border-0 shadow-sm">
                <div style="height: 150px;">
                    <img src="/media/equipment/eq_marine.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div class="card-body p-2 bg-light"><h6 class="font-weight-bold mt-2">海域地层模拟</h6></div>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '40px', '0']
      css_class: "bg-light"

  # ============================================================
  # 3. 模型构建技术能力 (8个) - 已修改为悬浮放大
  # ============================================================
  - block: markdown
    content:
      title: 模型构建技术能力
      subtitle: Modeling Capabilities
      text: |
        <p class="text-muted text-center mb-5">具备构建各类复杂地质目标体的能力，精确模拟地下介质的几何形态与物理属性。</p>
        <div class="container-fluid">
          <div class="row">
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_structure.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">构造和层位模拟</h5>
                  <p class="small text-muted mb-0">模拟褶皱、断层及不整合面构造。</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_velocity.jpg" class="zoom-img" style="object-fit: contain;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">速度、密度模拟</h5>
                  <p class="small text-muted mb-0">精确调配材料，实现全速度谱模拟。</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_sand.jpg" class="zoom-img" style="object-fit: contain;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">砂体储层模拟</h5>
                  <p class="small text-muted mb-0">构建河道、透镜体等复杂砂体模型。</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_cave.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">缝洞储层模拟</h5>
                  <p class="small text-muted mb-0">模拟碳酸盐岩溶洞及“串珠”反射。</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_attenuation.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">地层衰减模拟</h5>
                  <p class="small text-muted mb-0">不同Q值介质的能量吸收特性研究。</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_fluid.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">含油气性模拟</h5>
                  <p class="small text-muted mb-0">孔隙流体注入与AVO响应分析。</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_fracture_photo.jpg" class="zoom-img" style="object-fit: cover;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">各向异性介质</h5>
                  <p class="small text-muted mb-0">HTI/VTI 裂缝介质物理模型制作。</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-4">
              <div class="d-flex align-items-center border rounded p-3 h-100 shadow-sm bg-white">
                <div class="mr-3" style="width: 140px; height: 100px; flex-shrink: 0;">
                    <img src="/media/equipment/sim_fracture_diag.jpg" class="zoom-img" style="object-fit: contain;">
                </div>
                <div>
                  <h5 class="text-primary font-weight-bold mb-1">裂缝参数设计</h5>
                  <p class="small text-muted mb-0">精确控制裂缝密度、张开度与充填物。</p>
                </div>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '60px', '0']

  # ============================================================
  # 4. 典型应用案例 (10个案例) - 已修改为悬浮放大
  # ============================================================
  - block: markdown
    content:
      title: 典型应用案例
      subtitle: Case Study Examples
      text: |
        <div class="container-fluid px-4">
          <div class="row g-4">
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">1. 复杂构造与沉积扇体模拟</h4>
                </div>
                <div class="p-0" style="position: relative;"> <img src="/media/equipment/lab_example/example1.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case1" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">2. 碳酸盐岩溶洞模型</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example2.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case2" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">3. 页岩气储层各向异性模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example3.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case3" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">4. 深海浊积扇体模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example4.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case4" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">5. 火山岩储层物理模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example5.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case5" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">6. 煤层气储层裂缝模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example6.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case6" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">7. 盐丘构造物理模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example7.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case7" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">8. 致密砂岩气藏模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example8.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case8" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">9. 断陷盆地层序模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example9.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case9" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6 mb-5">
              <div class="card h-100 border rounded shadow-sm bg-white">
                <div class="p-3 bg-light">
                  <h4 class="text-dark mb-0">10. 潜山油气藏物理模拟</h4>
                </div>
                <div class="p-0" style="position: relative;">
                  <img src="/media/equipment/lab_example/example10.png" class="img-fluid zoom-img" style="height:350px; width:100%; object-fit:contain;">
                </div>
                <div class="p-3 d-flex justify-content-end">
                  <a href="/equipment/cases/case10" class="text-primary text-decoration-none">
                    <i class="fas fa-external-link-alt me-1"></i> 查看详情及数据
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '60px', '0']
      css_class: "bg-light"
---