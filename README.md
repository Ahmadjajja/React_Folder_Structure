# React_Folder_Structure

𝑩𝒆𝒔𝒕 𝑭𝒐𝒍𝒅𝒆𝒓 𝑺𝒕𝒓𝒖𝒄𝒕𝒖𝒓𝒆 𝒇𝒐𝒓 𝑹𝒆𝒂𝒄𝒕 𝑫𝒆𝒗𝒆𝒍𝒐𝒑𝒆𝒓𝒔:
In start, I always wondered what is the #best #practice for me to #structure my code. and with time I created this mental model to divide my #project based on #features. So today, I wanted to share my structure with you.
src/ <br />
├── assets/ <br />
│  ├── images/ <br />
│  ├── fonts/ <br />
│  └── styles/ <br />
├── components/ <br />
│  ├── common/ <br />
│  │  ├── Button/ <br />
│  │  ├── Input/ <br />
│  │  ├── Dropdown/ <br />
│  │  └── ... <br />
│  ├── feature1/ <br />
│  │  ├── Feature1Component1/ <br />
│  │  ├── Feature1Component2/ <br />
│  │  ├── Feature1Component3/ <br />
│  │  └── ... <br />
│  ├── feature2/ <br />
│  │  ├── Feature2Component1/ <br />
│  │  ├── Feature2Component2/ <br />
│  │  ├── Feature2Component3/ <br />
│  │  └── ... <br />
│  └── ... <br />
├── pages/ <br />
│  ├── Home/ <br />
│  │  ├── Home.js <br />
│  │  └── ... <br />
│  ├── About/ <br />
│  ├── Contact/ <br />
│  └── ... <br />
├── services/ <br />
│  ├── api.js <br />
│  ├── authService.js <br />
│  └── ... <br />
├── utils/ <br />
│  ├── helpers.js <br />
│  ├── validators.js <br />
│  └── ... <br />
├── App.js<br />
├── index.js <br />
└── ... <br />

𝑬𝒙𝒑𝒍𝒂𝒏𝒂𝒕𝒊𝒐𝒏: <br />

𝗮𝘀𝘀𝗲𝘁𝘀: This folder contains all #static assets, such as images, fonts, and stylesheets. <br />
𝗰𝗼𝗺𝗽𝗼𝗻𝗲𝗻𝘁𝘀: This folder contains all #reusable and #feature-specific #components. The common folder contains all common components that are shared across features. <br /> The feature-specific folders contain all components that are specific to each feature. <br />
𝗽𝗮𝗴𝗲𝘀: This folder contains all #top-#level components that are rendered by the #router. Each page should have its folder that contains the page component and any necessary sub-components. <br />
𝘀𝗲𝗿𝘃𝗶𝗰𝗲𝘀: This folder contains all #API and #authentication #services. <br />
𝘂𝘁𝗶𝗹𝘀: This folder contains all #utility #functions that can be shared across the #application. <br/>
𝗔𝗽𝗽.𝗷𝘀: This is the entry point of the application that contains the router. <br />
𝗶𝗻𝗱𝗲𝘅.𝗷𝘀: This is the file that #renders the App component to the #DOM. <br />

𝗡𝗼𝘁𝗲: I use #vite instead of create-react-app. It's much faster, lighter, have less reload time and only download #node #packages/modules along the way as they are needed. <br />
#softwareengineer #softwaredeveloper #computerscience #coding #programming #react #reactjs #angular #angularjs #mernstack #mernstackdeveloper #seniorengineer #projectmanagement
