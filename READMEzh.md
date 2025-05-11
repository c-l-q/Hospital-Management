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
