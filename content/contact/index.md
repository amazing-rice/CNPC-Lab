---
# ==============================
# 页面元数据配置
# ==============================
title: Contact
date: 2022-10-24
type: landing

sections:
  # ==============================
  # 第 1 部分：核心内容区 (联系方式 + 研究方向 + 招生合作)
  # ==============================
  - block: markdown
    content:
      title: 联系我们
      subtitle: ""
      text: |
        <div style="text-align: center;">
          <p style="color: gray;">欢迎对地球物理、地震模拟感兴趣的专家学者及同学来访交流。</p>
          <p style="line-height: 1.8;">
            <strong>📍 地址：</strong>北京市昌平区府学路18号 中国石油大学（北京）<br>
            <strong>👤 联系人：</strong>丁拼博<br>
            <strong>📞 电话：</strong>18618415157 (微信同号)<br>
            <strong>📧 邮箱：</strong>dingpinbo@cup.edu.cn
          </p>
        </div>

        ---

        ### 🔬 课题研究方向

        我们的团队致力于解决复杂油气及新能源领域的关键地球物理问题，主要研究方向包括：

        * **弹性波勘探基础理论与方法**
        * **天然气水合物实验及地球物理识别**
        * **页岩油、页岩气等非常规致密油气**
        * **裂缝、碳酸盐岩储层地震识别和预测**
        * **CCUS 碳封存实验模拟和地球物理监测**

        > **核心技术领域**：
        > `岩石物理` `地震物理模拟` `数据处理` `地震反演` `储层预测`

        ---

        ### 🎓 硕博招生

        **我们正在寻找对地球物理充满热情的你！**

        * **招收专业**：
            * 勘查技术与工程（勘探地球物理）
            * 地球物理学 / 物理学 / 数学
            * 计算机科学与技术 / 数据科学与大数据
        
        > 📢 **加入我们**：如果你有热情与兴趣加入CNPC物探重点实验室大家庭，请将简历发送到 **dingpinbo@cup.edu.cn**，我们将与你取得联系！

        ---

        ### 🤝 合作意向

        CNPC物探重点实验室团队依托**油气资源与工程全国重点实验室**，拥有先进的大型气浮三维地震物理模型实验系统。我们诚挚欢迎能源企业及科研机构在以下领域开展深度合作：

        1.  **非常规油气攻关**：针对页岩油气及致密油气储层，联合开展岩石物理实验与甜点预测研究。
        2.  **双碳技术应用**：利用物理模拟技术，开展 CCUS 碳封存监测与安全性评估研究。
        3.  **复杂储层预测**：针对缝洞型碳酸盐岩等复杂目标，提供高精度地震识别与反演技术服务。

    design:
      columns: '1'
      spacing:
        padding: ['50px', '0', '50px', '0']

  # ==============================
  # 第 2 部分：底部装饰图片
  # ==============================
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: ""
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg  # 确保图片在 assets/media/contact.jpg
          filters:
            brightness: 0.6
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['120px', '0', '120px', '0']
---