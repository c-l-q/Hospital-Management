<div align=“center">
<img src=“https：//readme-typing-svg.herokuapp.com？color=FFB13C&size=50&width=1000&height=80&lines=Welcome-to-Hospital-Management-App"/>
</迪夫>

HealthHub 是一个基于 React 的综合医院管理系统，旨在简化医疗保健运营并改善患者护理。
运用JavaScript（ES6+）、HTML5、CSS3 、Font Awesome图标技术构建的综合医院管理系统，
具备用户友好的响应式界面，可进行预约管理、维护患者记录、管理医生信息，设有管理工具。
其页面含主页、预约、患者、医生、管理员页，在部署方面，后端部署于 https://hospital-management-server-zeta.vercel.app/  。
对于想要安装使用该系统的用户，具体步骤如下：
1、克隆仓库：使用命令  git clone https://github.com/yazdanhaider/Hospital-Management.git  ，将项目仓库克隆到本地，获取系统的源代码。
2、导航至项目目录：在命令行中输入 cd Hospital-Management ，进入项目所在的目录，为后续作做好准备。
3、安装依赖项：执行  npm i  命令，自动安装项目运行所需的各类依赖包，确保系统功能的完整性。
4、运行开发服务器：通过  npm run dev  启动开发服务器，使系统能够在本地环境中正常运行，方便进行调试和测试。
在实际使用过程中，用户可以通过顶部导航栏轻松浏览系统的不同部分，快速定位到所需功能模块；
使用预约表单进行新预约的安排，操作流程简洁明了；
在患者管理部分，对患者记录进行添加、编辑、删除等操作，实现患者信息的动态管理；
在医生信息部分，查看和管理医生的相关资料，合理安排医疗人员工作；
管理员可以使用 “admin” 作为用户名和密码登录 Admin 面板，访问管理功能，进行系统的高级管理作。

<!-- by 莫杰 -->

## 安装与设置指南
1. 安装 Node.js:
   ```
  访问 https://nodejs.org/zh-cn/download 下载并安装 Node.js。
   ```
2. 克隆仓库:
   ```
   git clone https://github.com/yazdanhaider/Hospital-Management.git
   ```
3. 进入后端项目目录:
   ```
   cd Hospital-Management Backend
   ```
4. 安装后端依赖:
   ```
   npm install
   ```
5. 启动后端服务器:
   ```
   npm run dev
   ``` 
6. 进入前端项目目录（在新终端中执行）:
   ```
   cd Hospital-Management Frontend
   ```
7. 安装前端依赖:
   ```
   npm install
   ```
8. 启动前端开发服务器:
   ```
   npm run dev
   ``` 
<!-- by 罗钰慧 -->


## Technologies Used

- **ReactJs**  
  Build modern, responsive front-end interfaces with a component-based architecture, leveraging state management and virtual DOM for optimal performance.

- **JavaScript (ES6+)**  
  Utilize modern syntax features such as arrow functions, destructuring, and async/await, combined with modular development (import/export) for improved code readability and maintainability.

- **HTML5**  
  Provide the structural foundation with semantic markup (e.g., `<header>`, `<nav>`, `<main>`) to enhance SEO and accessibility.

- **CSS3**  
  Implement styling and animations with modular CSS and responsive design principles to ensure consistent cross-device rendering.

- **Font Awesome**  
  Integrate a comprehensive library of vector icons to enhance visual appeal and user experience, supporting custom icon styling.

- **jsPDF**  
  Enable front-end PDF report generation for data export and printing, with customizable report formatting and content.

- **Other Key Dependencies**  
  - **React Router DOM**: Manage routing for single-page applications  
  - **Framer Motion**: Create smooth animations and transitions  
  - **Axios**: Handle HTTP requests for API data interactions  
  - **MongoDB & Mongoose**: Build database models and ensure data persistence  
  - **NextAuth**: Implement user authentication and authorization  
  - **React Datepicker**: Provide intuitive date selection components
<!-- by 农氏线 -->


使用方法

-通过顶部导航栏在不同板块间切换:
板块间切换操作：在页面顶部，设有直观清晰的导航栏，是一个网页导航栏。涵盖多个核心板块，其中 “Health Nest” 是网站名称，可直译为 “健康巢” 。导航栏上有 “Home（首页）”“Appointments（预约）”“Patients（患者）”“Doctors（医生）”“About（关于）”“Contact（联系）” 等 ，方便用户在不同页面间跳转。此外，还有 “Sign Up（注册）” 和 “Log In（登录）” 仅需轻点对应文字标签或图标，即可快速、流畅地切换至目标板块，获取不同类型的信息与服务。例如，点击“Doctors（医生）”，可以看到很多医生的信息，从而进行选择。
板块间切换操作：在页面顶部，设有直观清晰的导航栏，是一个网页导航栏。涵盖多个核心板块，其中 “Health Nest” 是网站名称，可直译为 “健康巢” 。导航栏上有几大板块，方便用户在不同页面间跳转。
1. Home（首页）：点击可返回网站首页，获取网站的主要信息和功能入口。
 
2. Appointments（预约）：用于进入预约相关的界面，安排服务预约。
 
3. Patients（患者）：展示与患者相关的信息，如患者账户管理、患者相关数据等。
 
4. Doctors（医生）：点击可查看网站上的医生信息，以便用户选择合适的医生。
 
5. About（关于）：介绍网站的背景、宗旨、发展历程等相关信息。
 
6. Contact（联系）：提供与网站相关的联系方式，如客服邮箱、电话等。
 
7. Sign Up（注册）：新用户可点击此选项进行注册，创建自己的账户。
 
8. Log In（登录）：已有账户的用户点击登录，输入正确的账号密码后进入个人账户。


-使用预约表单安排新的预约
预约流程指引：若您有服务预约需求，可通过以下步骤完成新预约：
1.预约流程指引：若您有服务预约需求，可通过以下步骤完成新预约：
首先，点击导航栏中的“Appointments（预约）”,进入预约界面；
接着，按提示依次填写病人姓名、选择预约的医生、预约日期及时间段以及主要的信息；
2.接着，按提示依次填写病人姓名、选择预约的医生、预约日期及时间段以及主要的信息；
填写完成后，请仔细核对各项内容，确保信息准确无误；
最后，点击「提交」按钮，系统将即时响应并生成预约确认提示。您可在「我的预约」中查看预约详情，如有问题也可随时联系在线客服协助处理。
3.最后，点击「提交」按钮，系统将即时响应并生成预约确认提示。您可在「我的预约」中查看预约详情，如有问题也可随时联系在线客服协助处理。
                                                        <!--by 莫莉华-->

页面
主页：可快速访问主要功能的欢迎页面。 
## 1.在HomePage.jsx和Home.jsx 

HomePage.jsx的代码 "只包含欢迎标题"， 
    <Layout>
      <h1 className="text-3xl font-bold text-center my-8">Welcome to Hospital Management System</h1>
      {/* Add more sections or components as needed */}
    </Layout>
    通过  <Layout>  组件引入 Header 和其他布局元素。

Home.jsx的代码 
有完整的主页实现
   包含丰富的功能：
     英雄区域(Welcome to Health Nest)
     特色功能展示(6个医疗相关功能)
     关于我们部分(带图片轮播)
     患者评价轮播
     行动号召区域(Sign Up)
     评论组件(Review)
   使用了动画效果(motion)和响应式设计
   包含多个子组件和外部库(如react-slick)

## 2.医院管理系统主页 - 功能、项目介绍与效果

1. 主要功能
欢迎区域
大标题动画显示"Welcome to Health Nest"  
副标题展示系统简介  
"Get Started"按钮（跳转至注册页）  

核心特色功能展示（6项）  
现代化医疗设施（'FaHospital'）  
专业医疗团队（'FaUserMd'）  
便捷预约系统（'FaCalendarCheck'）  
全面医疗服务（'FaHeartbeat'）  
24/7急救服务（'FaAmbulance'）  
远程医疗支持（'FaLaptopMedical'）  

关于我们
图片轮播展示医院环境  
文字介绍系统目标和优势  
"Learn More"按钮（跳转至关于页面）  

患者评价 
轮播展示6条患者评价  
包含用户头像、姓名和评语  
悬停动画效果  

行动号召（CTA）
鼓励用户注册（"Sign Up Now"按钮）  

动画与交互
使用framer-motion实现滚动、悬停动画  
响应式设计（适配手机、平板、电脑）  

2. 项目介绍 
项目名称：Health Nest（医院管理系统）  
技术栈：  
前端：React.js + Tailwind CSS  
动画库：Framer Motion  
图标：React Icons（Font Awesome）  
轮播组件：react-slick  

代码结构：  
HomePage.jsx：主页入口，负责整体布局（如导航栏、页脚）。  
Home.jsx：主页核心内容，包含所有功能模块。  

设计特点：  
现代化UI，圆角卡片+阴影效果  
医疗主题配色（蓝、白、橙）  
移动端优先，适配不同屏幕尺寸  


3. 实现效果
动态视觉效果：  
文字渐显、按钮缩放、卡片悬停上浮  
平滑的图片轮播和评价滑动  

用户友好交互：  
点击按钮跳转至对应功能页（如注册、关于）  
轮播自动播放，支持手动切换  

响应式布局：  
  电脑端：3列功能展示  
  平板端：2列  
  手机端：1列（内容堆叠）  





预约：预约和管理患者预约。   
在Server.jsx和Appointments.jsx
1. Services.jsx
定位：服务列表展示页
预约相关内容：
在服务列表中包含 "Appointment Scheduling"（预约排班） 项
仅作为文字说明，无实际功能
作用：  
  向用户说明系统支持预约功能，但需跳转到其他页面（如Appointments.jsx）才能操作。


2. Appointments.jsx
定位：完整的预约管理功能页

核心功能：
  新建预约  
表单包含患者姓名、选择医生、日期时间、备注  
使用 DatePicker 组件选择时间  
输入验证（姓名格式、未来时间校验）
  管理预约
搜索预约（按患者名或医生名）  
标记预约为“已完成”  
删除预约  
  数据展示
卡片式布局显示预约详情（患者、医生、时间、状态）  
状态标签（Scheduled/Completed）  
操作按钮（编辑、删除、完成）

技术实现：  
  使用 useState 管理状态  
  动画效果（framer-motion）  
  响应式设计（适配手机/电脑）

## 1. Services.jsx 的功能、项目介绍与效果

功能
服务列表展示：静态列出医院管理系统的主要功能，包括：  
患者管理（Patient Management）  
预约排班（Appointment Scheduling）  
电子健康记录（EHR）  
账单管理（Billing and Invoicing）  
药品库存管理（Inventory Management）  
员工管理（Staff Management）  
数据分析（Reporting and Analytics）  
远程医疗（Telemedicine Integration）  

项目介绍 
定位：服务介绍页，用于向用户说明系统提供的功能。  
技术实现：  
使用 React 构建静态页面。  
采用 Tailwind CSS 进行简单样式布局。  
无动态数据交互，仅渲染固定内容。  

效果  
UI 示例：  
  ```plaintext
  Our Services
  • Patient Management
  • Appointment Scheduling
  • Electronic Health Records
  • Billing and Invoicing
  • ...（其他服务项）
  ```
交互：  
纯静态页面，无点击事件或表单提交。  
适合作为系统功能概览页，引导用户进入具体功能模块。  

##( 代码结构：

- 基础布局：通过  <Layout>  组件引入头部和页脚。

- 内容结构：使用卡片式布局（圆角+阴影）分点列出功能，搭配图标（如  FaList ）增强识别。

效果

1. 视觉设计：

- 医疗主题配色（主色：蓝色，辅助色：白色/橙色）。

- 每个功能项含图标+标题，简洁清晰（例： FaUserGroup  对应“患者管理”）。

2. 交互体验：

- 预约排班 文字可点击（或带箭头图标），提示用户跳转至  Appointments.jsx  操作。

- 响应式布局：手机端堆叠显示，电脑端分两列/三列排列。

3. 作用：

- 快速传达系统能力，引导用户进入具体功能模块（如预约管理）。)

## 2. Appointments.jsx 的功能、项目介绍与效果 

 功能 
预约管理全流程：  
新建预约：填写患者姓名、选择医生、设定时间、添加备注。  
搜索预约：按患者或医生姓名实时筛选。  
状态管理：标记预约完成（Completed）或删除预约。  
数据验证：确保患者姓名合法、预约时间在未来。  
动态数据模拟：  
默认展示 2 条预约数据（可扩展为 API 请求）。  
提供 3 名医生选项（可扩展为动态加载）。  

 项目介绍  
定位：核心业务页，提供完整的预约增删改查（CRUD）功能。  
技术实现：  
React Hooks（useState, useContext）管理状态。  
Framer Motion 实现动画（表单弹出、卡片悬停）。  
React DatePicker 选择预约时间。  
权限控制：未登录用户跳转至登录页（依赖 LoginContext）。  
响应式布局：适配手机、平板、电脑（Tailwind CSS 网格）。  

 效果 
UI 示例：  
  顶部操作栏：  
“新建预约”按钮（点击展开表单）。  
搜索框（实时过滤预约）。  
  预约卡片：  
显示患者、医生、时间、状态（Scheduled/Completed）。  
操作按钮（删除、标记完成）。  
  表单弹窗：  
    - 带输入验证的预约提交表单。  
  交互体验：  
动画：表单渐显、卡片悬停上浮。  
即时反馈：输入错误时弹出提示。  
<!--by:chenliqin-->
