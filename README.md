# Google geofence SDK集成-审核原因

### 中文版本

**致Google Play审核团队：**

我们申请后台位置权限（通过集成Geofence SDK）是为了实现探探（Tantan）产品的核心社交功能、提升用户体验并保障社区安全。具体理由如下：

**一、 核心功能必要性**

1.  **基于地理位置的匹配与发现**：获取位置信息是探探作为LBS社交产品的核心基础。此权限使我们能够为用户实时推荐附近的其他用户，促成线上匹配与线下见面，这是产品解决用户需求（发现身边人）的根本方式。

2.  **本地活动通知**：为了增加用户的连接场景和互动机会，我们需要向特定区域（如商圈、大学城、活动场馆周边）的用户，推送其所在地正在发生的线下社交活动、主题聚会或热门约会地点信息，帮助用户从线上走到线下。

**二、 补充说明与用户价值**

1.  **提升安全与信任度**：利用地理围栏技术，我们可以在一定程度上辅助验证用户声称所在地的真实性，有助于识别和抑制虚假位置、欺诈账号，构建更真实的社交环境。

2.  **提供个性化内容**：根据用户所在的区域，推送更相关的本地化内容（例如，本市的约会攻略、节假日特别活动），或符合地区法律法规的广告信息，提升内容的相关性和用户体验。

3.  **优化产品与服务效率**：通过理解用户分布，我们可以在不同区域动态优化服务策略（如在用户密集区提升匹配计算频率，在非活跃区减少不必要的服务器请求），从而实现更智能的资源分配和功能响应。

**三、 权限使用承诺**

我们郑重承诺：

*   后台位置权限**仅用于**实现上述基于地理围栏的触发功能，**不会**用于持续、后台静默地追踪用户的行踪轨迹。

*   用户拥有完全的控制权，可以在设备系统设置中随时关闭此权限，且我们的应用提供了清晰的权限使用说明。

*   所有位置数据的收集、使用和处理均严格遵守我们的《隐私政策》等相关数据保护法规。

感谢您的审核，我们随时准备提供更多细节或技术说明。

### 英文版本

**To the Google Play Review Team:**

We are applying for background location permission (via integrating the Geofence SDK) to enable the core social functionalities of Tantan, enhance user experience, and ensure community safety. The detailed justifications are as follows:

**1. Core Functional Necessity**

*   **Location-Based Matching and Discovery:**​ Acquiring location data is fundamental to Tantan as an LBS social product. This permission allows us to recommend nearby users in real-time, facilitating online matches and potential offline meetings. This is the essential method by which our product addresses user needs (discovering people around them).

*   **Local Event and Opportunity Notifications:**​ To create more connection scenarios and interaction opportunities, we need to send notifications about local offline social events, themed gatherings, or popular dating spots to users in specific areas (e.g., shopping districts, university towns, event venues). This helps users transition from online interaction to offline meetings.

**2. Supplementary Explanations & User Value**

*   **Enhancing Safety and Trust:**​ Utilizing geofencing technology helps us preliminarily verify the authenticity of a user's claimed location, aiding in the identification and deterrence of fake locations and fraudulent accounts, thereby fostering a more genuine social environment.

*   **Delivering Personalized Content:**​ We can provide more relevant localized content (e.g., dating guides for the user's city, special holiday events) or advertisements compliant with local laws and regulations based on the user's region, improving content relevance and user experience.

*   **Optimizing Product and Service Efficiency:**​ Understanding user distribution allows us to dynamically optimize service strategies in different areas (e.g., increasing match calculation frequency in user-dense areas, reducing unnecessary server requests in inactive zones). This leads to smarter resource allocation and feature responsiveness.

**3. Permission Use Commitment**

We solemnly commit that:

*   The background location permission is **used solely**​ for enabling the geofence-triggered features described above. It is **NOT**​ used for continuous, silent background tracking of user movement.

*   Users have full control and can disable this permission at any time in their device settings. Our app provides clear explanations of permission usage.

*   All collection, use, and processing of location data strictly comply with our Privacy Policy and relevant data protection regulations.

Thank you for your review. We are ready to provide further details or technical explanations if needed.
