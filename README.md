
### Project Overview
---------

This React-based application provides functionality to control and management of autonomous mobile robots (AMRs)- its primary focus is on providing a user-friendly experience for effective AMR management.

### Prerequisites

*   **Node.js:** Version 18 or higher
    
*   **npm:** (or yarn) Package manager
    
*   **React Developer Tools:** Recommended for development and debugging
    

### Installation

    git clone [(https://github.com/openAMRobot/OpenAMR_UI_dev)](https://github.com/openAMRobot/OpenAMR_UI_dev)
    
    cd OpenAMR_UI_dev
    
    npm install 
    

### Development

#### Running the application locally

To start the development server:

    npm run dev  

This will launch the application in development mode. You can access it at http://localhost:3000 (or a different port if specified). The browser will automatically reload when changes are made.

#### Building for production

To create an optimized build for production:

    npm run build  

This will generate a build folder containing the production-ready version of your application.

### Project Structure

*   **build:** builded files.

*   **src:** Contains the source code of the application.
    
    *   **app:** ettings for entire project, configs, providers etc. Top app layer.
    
    *   **assets:** assets such as images, fonts, etc
    
    *   **components:** most lower-level logic items of the app
        
    *   **layouts:** website layout layer that wrap pages for reusing components such as header, footer etc.
        
    *   **pages:** pages layer, each of them have their own route, link several components into a coherent logical unit
        
    *   **shared:** entities that can be used on any level of the app: styles, jsons, constants etc
        
    *   **stores:** entities and logic that lives during all website lifecycle and the bus that transfers data between components and pages of the application
        
*   **public:** public resources like libraries, etc. Files that placed to build directory without any conversion or minification
  
    *   **ros:** different ros or js libraries
    
*   **package.json:** Project dependencies and scripts
    
