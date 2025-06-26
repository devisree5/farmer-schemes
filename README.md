# 🌱 Agricultural Program Application & Tracking System  

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://devisree5.github.io/agriculture-portal/)  

A **fully functional** web portal for farmers to browse government agricultural schemes, apply for programs, and track applications. Built with modern HTML, CSS, and JavaScript.  


## ✨ Features  

✅ **User-Friendly Interface**  
- Clean, responsive design  
- Intuitive navigation  

✅ **Complete Functionality**  
- Browse available programs  
- Submit applications  
- Track application status  
- User authentication (login/logout)  

✅ **Data Persistence**  
- Saves user data and applications (using `localStorage`)  

✅ **Modern UI**  
- Card-based program display  
- Interactive forms  
- Mobile-friendly layout  

## 🛠️ Technologies Used  

- **Frontend**:  
  ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)  

- **Design**:  
  ![Responsive Design](https://img.shields.io/badge/-Responsive-Design-4285F4)  

## 🚀 Getting Started  

### Prerequisites  
- Modern web browser (Chrome, Firefox, Edge)  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/agriculture-portal.git
   ```
2. Open `index.html` in your browser.  

## 📂 Project Structure  

```
agriculture-portal/
├── index.html          # Main application
├── README.md           # This file
└── screenshot.png      # Project screenshot
```

## 🌐 Usage  

1. **Browse Programs**:  
   - Click "Explore Programs" to view available schemes  
   - Filter by status (Open/Closed)  

2. **Apply for Programs**:  
   - Login/Register first  
   - Click "Apply Now" on any program  
   - Fill out the application form  

3. **Track Applications**:  
   - View your dashboard  
   - See all submitted applications  

## 🛠️ Customization  

To add more programs, edit the `programs` array in the JavaScript section (~line 1120):  
```javascript
const programs = [
    {
        id: 1,
        title: "New Program Name",
        description: "Program details...",
        status: "open",
        deadline: "2023-12-31",
        image: "path/to/image.jpg"
    },
    // Add more programs...
];
```


## 🙏 Acknowledgments  
- Images from [Unsplash](https://unsplash.com)  
- Icons from [Shields.io](https://shields.io)  

---

**🌟 Happy Farming!**  
*For support, open an issue or contact [your email]*  

