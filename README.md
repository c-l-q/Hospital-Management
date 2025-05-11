<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=FFB13C&size=50&width=1000&height=80&lines=Welcome-to-Hospital-Management-App"/>
</div>

HealthHub is a comprehensive React-based hospital management system designed to streamline healthcare operations and improve patient care. A comprehensive hospital management system is built using JavaScript (ES6+), HTML5, CSS3, and Font Awesome icon technology. It has a user-friendly responsive interface and enables functions such as appointment management, maintenance of patient records, management of doctor information, and provides management tools. The pages of the system include a homepage, an appointment page, a patient page, a doctor page, and an administrator page.
For the deployment, the backend is deployed at https://hospital-management-server-zeta.vercel.app/.
For users who want to install and use this system, the specific steps are as follows: Clone the repository: Use the command git clone https://github.com/yazdanhaider/Hospital-Management.git to clone the project repository to the local machine and obtain the source code of the system. Navigate to the project directory: Enter cd Hospital-Management in the command line to enter the directory where the project is located, getting ready for subsequent operations. Install dependencies: Execute the npm i command to automatically install all kinds of dependency packages required for the project to run, ensuring the integrity of the system functions. Run the development server: Start the development server by using the npm run dev command, allowing the system to run properly in the local environment, which is convenient for debugging and testing.
During the actual use, users can easily browse different parts of the system through the top navigation bar and quickly locate the required functional modules. They can use the appointment form to arrange new appointments, and the operation process is simple and clear. In the patient management section, operations such as adding, editing, and deleting patient records can be carried out to achieve dynamic management of patient information. In the doctor information section, relevant information of doctors can be viewed and managed to reasonably arrange the work of medical staff. Administrators can log in to the Admin panel using "admin" as both the username and password to access management functions and perform advanced management operations on the system.

<!-- by 莫杰 -->

## Setup and Installation
1. Install Node.js:
   ```
   Visit https://nodejs.org/en/download to download and install Node.js.
   ```
2. Clone the repository:
   ```
   git clone https://github.com/yazdanhaider/Hospital-Management.git
   ```
3. Navigate to the Backend Project Directory:
   ```
   cd Hospital-Management Backend
   ```
4. Install dependencies:
   ```
   npm install
   ```
5. Run the Backend Server:
   ```
   npm run dev
   ``` 
6. Navigate to the Backend Project Directory:
   ```
   cd Hospital-Management/Frontend
   ```
7. Install dependencies:
   ```
   npm install
   ```
8. Run the Backend Server:
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
  - <!-- by 农氏线 -->

**Usage**

- **Switch between different sections via the top navigation bar**:
The operation of switching between sections: There is an intuitive and clear web navigation bar at the top of the page. It covers multiple core sections. The website is named "Health Nest". The navigation bar includes "Home", "Appointments", "Patients", "Doctors", "About", "Contact", etc. Additionally, there are "Sign Up" and "Log In". Just tap on the corresponding text labels or icons, and you can quickly and smoothly switch to the target section to obtain different types of information and services. For example, by clicking on "Doctors", you can view the information of many doctors and then make a selection.
The operation of switching between sections: There is an intuitive and clear web navigation bar at the top of the page. It covers multiple core sections. The website is named "Health Nest". There are several major sections on the navigation bar, which is convenient for users to jump between different pages.
1. **Home**: Click to return to the website's homepage and access the main information and functional entrances of the website.
2. **Appointments**: Used to enter the appointment-related interface and arrange service appointments.
3. **Patients**: Displays information related to patients, such as patient account management, patient-related data, etc.
4. **Doctors**: Click to view the information of doctors on the website so that users can select suitable doctors.
5. **About**: Introduces relevant information such as the background, purpose, and development history of the website.
6. **Contact**: Provides contact information related to the website, such as the customer service email address and telephone number, etc.
7. **Sign Up**: New users can click this option to register and create their own accounts.
8. **Log In**: Existing users click to log in and enter their personal accounts after entering the correct account and password.

- **Arrange new appointments using the appointment form**
Guidance on the appointment process: If you have a need for service appointments, you can complete a new appointment through the following steps:
1. Guidance on the appointment process: If you have a need for service appointments, you can complete a new appointment through the following steps:
First, click "Appointments" in the navigation bar to enter the appointment interface.
Next, fill in the patient's name, select the doctor for the appointment, the appointment date and time period, and other main information in sequence according to the prompts.
2. Next, fill in the patient's name, select the doctor for the appointment, the appointment date and time period, and other main information in sequence according to the prompts.
After filling it out, carefully check all the contents to ensure the accuracy of the information.
Finally, click the "Submit" button. The system will respond immediately and generate an appointment confirmation prompt. You can view the appointment details in "My Appointments", and if there are any problems, you can contact the online customer service for assistance at any time.
3. Finally, click the "Submit" button. The system will respond immediately and generate an appointment confirmation prompt. You can view the appointment details in "My Appointments", and if there are any problems, you can contact the online customer service for assistance at any time. 
                                                   <!--by 莫莉华 -->


## Pages

1. **Home**: Welcome page with quick access to key features.
## 1. In HomePage.jsx and Home.jsx

## HomePage.jsx code
It only contains a welcome title.
```jsx
<Layout>
  <h1 className="text-3xl font-bold text-center my-8">Welcome to Hospital Management System</h1>
  {/* Add more sections or components as needed */}
</Layout>
```
It introduces the `Header` and other layout elements through the `<Layout>` component.

### Home.jsx code
It has a complete implementation of the home page.
It includes rich features:
 Hero area ("Welcome to Health Nest")
 Featured function display (6 medical-related functions)
 About Us section (with image carousel)
 Patient reviews carousel
 Call-to-Action area ("Sign Up")
 Review component
It uses animation effects (`motion`) and responsive design.
It contains multiple sub-components and external libraries (such as `react-slick`).

## 2. Hospital Management System Home Page - Features, Project Introduction and Effects

## 1. Main Features
Welcome Area
 The large title is animated to display "Welcome to Health Nest".
 The subtitle shows an introduction to the system.
 "Get Started" button (jumps to the registration page).
Core Featured Functions Display (6 items)
 Modern medical facilities ('FaHospital')
 Professional medical team ('FaUserMd')
 Convenient appointment system ('FaCalendarCheck')
 Comprehensive medical services ('FaHeartbeat')
 24/7 emergency services ('FaAmbulance')
 Telemedicine support ('FaLaptopMedical')
About Us
 Image carousel shows the hospital environment.
 Text introduction of the system's goals and advantages.
 "Learn More" button (jumps to the about page).
Patient Reviews
 Carousel shows 6 patient reviews.
 Includes user avatars, names, and comments.
 Hover animation effect.
Call-to-Action (CTA)
 Encourages users to register ("Sign Up Now" button).

## Animation and Interaction
 Uses `framer-motion` to implement scrolling and hovering animations.
 Responsive design (adapts to mobile phones, tablets, and computers).

## 2. Project Introduction
Project Name: Health Nest (Hospital Management System)
Technology Stack:
 Front-end: React.js + Tailwind CSS
 Animation Library: Framer Motion
 Icons: React Icons (Font Awesome)
 Carousel Component: react-slick
Code Structure:
 HomePage.jsx: The entry point of the home page, responsible for the overall layout (such as the navigation bar and footer).
 Home.jsx: The core content of the home page, containing all functional modules.
Design Features:
 Modern UI with rounded corner cards + shadow effect.
 Medical-themed color scheme (blue, white, orange).
 Mobile-first, adapting to different screen sizes.

## 3. Implementation Effects
Dynamic Visual Effects:
 Gradual text appearance, button scaling, and card hovering and floating up.
 Smooth image carousel and review sliding.
User-Friendly Interaction:
  Clicking the button jumps to the corresponding function page (such as registration, about).
  The carousel plays automatically and supports manual switching.
Responsive Layout:
  On desktop: 3-column function display.
  On tablet: 2-column.
  On mobile phone: 1-column (content stacked).  

2. Appointments: Book and manage patient appointments.
## In Server.jsx and Appointments.jsx

 1. Services.jsx
Positioning: Service list display page
Appointment - related content:
Include the item "Appointment Scheduling" in the service list. It is only a text description without actual functionality.
Function:
Inform users that the system supports the appointment function, but they need to jump to other pages (such as Appointments.jsx) to perform operations.

## 2. Appointments.jsx
Positioning: A complete appointment management function page

Core functions:
 Create new appointments:
The form includes patient name, doctor selection, date and time, and remarks. Use the DatePicker component to select the time. Input validation (name format, future time verification).
 Manage appointments:
Search for appointments (by patient name or doctor name). Mark appointments as "completed". Delete appointments.
 Data display:
Display appointment details in a card layout (patient, doctor, time, status). Status labels (Scheduled/Completed). Action buttons (edit, delete, complete).

Technical implementation:
Use useState to manage state. Animation effects (framer - motion). Responsive design (compatible with mobile/desktop).

## 1. Functions, Project Introduction and Effects of Services.jsx

Functions
Service list display:
Static listing of the main functions of the hospital management system, including:
Patient Management
Appointment Scheduling
Electronic Health Records (EHR)
Billing and Invoicing
Drug Inventory Management
Staff Management
Data Analysis (Reporting and Analytics)
Telemedicine Integration

Project Introduction
Positioning: Service introduction page, used to inform users about the functions provided by the system.
Technical implementation:
Build a static page using React. Use Tailwind CSS for simple layout styling. There is no dynamic data interaction, only rendering fixed content.

Effects
UI example:
```plaintext
Our Services
• Patient Management
• Appointment Scheduling
• Electronic Health Records
• Billing and Invoicing
•... (other service items)
```
Interaction:
A purely static page with no click events or form submissions. It is suitable as an overview page of system functions to guide users to specific functional modules.

### Code Structure:
- **Basic Layout**: Introduce the header and footer through the `<Layout>` component.
- **Content Structure**: Use a card-style layout (rounded corners + shadows) to list functions item by item, and pair with icons (such as `FaList`) to enhance recognition.

### Effects
1. **Visual Design**:
    - Medical-themed color scheme (primary color: blue, secondary colors: white/orange).
    - Each function item contains an icon and a title, which is simple and clear (for example, `FaUserGroup` corresponds to "Patient Management").
2. **Interactive Experience**:
    - The text "Appointment Scheduling" is clickable (or accompanied by an arrow icon) to prompt users to jump to the `Appointments.jsx` for operations.
    - Responsive layout: Stacked display on mobile devices and arranged in two or three columns on desktop devices.
3. **Function**:
    - Quickly convey the system capabilities and guide users to enter specific functional modules (such as appointment management). 

### 2. Functions, Project Introduction and Effects of Appointments.jsx

Functions
Full - process appointment management:
 Create new appointments: Fill in patient name, select doctor, set time, and add remarks.
 Search for appointments: Real - time filtering by patient or doctor name.
 Status management: Mark appointments as completed or delete appointments.
 Data validation: Ensure that the patient name is legal and the appointment time is in the future.
 Dynamic data simulation:
By default, display 2 appointment data (can be extended to API requests). Provide 3 doctor options (can be extended to dynamic loading).

#### Project Introduction
Positioning: Core business page, providing complete appointment CRUD (Create, Read, Update, Delete) functions.
Technical implementation:
Use React Hooks (useState, useContext) to manage state. Use Framer Motion to implement animations (form pop - up, card hover). Use React DatePicker to select appointment time. Permission control: Redirect unlogged - in users to the login page (depends on LoginContext). Responsive layout: Compatible with mobile, tablet, and desktop (Tailwind CSS grid).

Effects
UI example:
 Top operation bar:
"Create new appointment" button (click to expand the form). Search box (real - time filtering of appointments).
 Appointment cards:
Display patient, doctor, time, and status (Scheduled/Completed). Action buttons (delete, mark as completed).
 Form pop - up window:
A reservation submission form with input validation.

Interaction experience:
 Animation: The form fades in, and the card hovers and floats up.
 Immediate feedback: Pop up a prompt when there is an input error.

 <!--by chenliqin-->
 222 changes: 222 additions & 0 deletions222  
READMEchenliqinzh.md
Viewed
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,222 @@


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


<!--by 陈丽芹 -->
