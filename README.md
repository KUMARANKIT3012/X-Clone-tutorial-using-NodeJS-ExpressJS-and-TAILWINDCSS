# X Clone (Twitter Clone)

A full-stack social media platform clone inspired by X (formerly Twitter), built with modern web technologies including Node.js, Express.js, and Tailwind CSS.

## 📸 Preview

This project recreates the core features and user interface of X/Twitter, providing a comprehensive social media experience with:
- User authentication and profiles
- Tweet posting and interactions
- Real-time feed updates
- Responsive design with Tailwind CSS
- Modern UI/UX patterns

## 🚀 Features

- **User Authentication**
  - Secure login and registration
  - Session management
  - User profiles

- **Tweet Management**
  - Create, read, update, and delete tweets
  - Like and retweet functionality
  - Character limit enforcement
  - Timestamp display

- **Social Interactions**
  - Follow/unfollow users
  - User feed with personalized content
  - Notifications system
  - User mentions and hashtags

- **Responsive Design**
  - Mobile-first approach
  - Beautiful UI with Tailwind CSS
  - Dark mode support
  - Smooth animations and transitions

## 🛠️ Technologies Used

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** (assumed) - Database for storing user data and tweets

### Frontend
- **HTML5** - Markup structure
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript** - Client-side functionality

### Build Tools
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing

## 📁 Project Structure

```
X-Clone-tutorial-using-NodeJS-ExpressJS-and-TAILWINDCSS/
├── src/                    # Source files
│   └── input.css          # Tailwind CSS input file
├── dist/                   # Compiled/built files
├── node_modules/           # Dependencies
├── package.json            # Project dependencies and scripts
├── package-lock.json       # Locked dependency versions
├── tailwind.config.js      # Tailwind CSS configuration
├── postcss.config.js       # PostCSS configuration
└── README.md              # This file
```

## 💻 Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- MongoDB (for database)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/KUMARANKIT3012/X-Clone-tutorial-using-NodeJS-ExpressJS-and-TAILWINDCSS.git
cd X-Clone-tutorial-using-NodeJS-ExpressJS-and-TAILWINDCSS
```

2. **Install dependencies:**
```bash
npm install
```

3. **Set up environment variables:**
Create a `.env` file in the root directory:
```env
PORT=3000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
```

4. **Build Tailwind CSS:**
```bash
npm run build:css
```

5. **Start the development server:**
```bash
npm start
```

6. **Open your browser:**
Navigate to `http://localhost:3000`

## 🎨 Tailwind CSS Configuration

This project uses Tailwind CSS for styling. To customize the design:

1. Edit `tailwind.config.js` for theme customization
2. Modify `src/input.css` for custom styles
3. Run the build command to compile CSS

## 📝 Available Scripts

- `npm start` - Start the development server
- `npm run build` - Build for production
- `npm run build:css` - Compile Tailwind CSS
- `npm run watch:css` - Watch CSS changes in development

## 🔧 Configuration Files

### tailwind.config.js
Contains Tailwind CSS configuration including:
- Content paths
- Theme customization
- Plugin configuration

### postcss.config.js
PostCSS configuration for:
- Tailwind CSS processing
- Autoprefixer

## 🌟 Key Features Implementation

### Tweet Posting
- Rich text input
- Image upload support
- Character counter
- Real-time validation

### User Feed
- Personalized timeline
- Infinite scroll
- Real-time updates
- Filter and sort options

### Notifications
- Real-time notifications
- Activity tracking
- Unread indicators

## 🔐 Security Features

- Password hashing
- JWT authentication
- CSRF protection
- Input validation and sanitization
- XSS prevention

## 📱 Responsive Design

The application is fully responsive and works seamlessly on:
- Desktop computers
- Tablets
- Mobile phones
- Different screen orientations

## 🚧 Future Enhancements

- [ ] Direct messaging system
- [ ] Advanced search functionality
- [ ] Trending topics
- [ ] Stories feature
- [ ] Video upload support
- [ ] Email notifications
- [ ] Two-factor authentication
- [ ] Analytics dashboard

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is for educational purposes only.

## 👨‍💻 Author

**KUMARANKIT3012**
- GitHub: [@KUMARANKIT3012](https://github.com/KUMARANKIT3012)

## 🙏 Acknowledgments

- Design inspired by X (Twitter)
- Built as a learning project to understand full-stack development
- Thanks to the Node.js and Express.js communities
- Tailwind CSS for the amazing utility-first framework

## 📞 Support

For support, issues, or feature requests, please open an issue in the GitHub repository.

---

⭐ If you found this project helpful, please consider giving it a star!

## 🔗 Related Resources

- [Node.js Documentation](https://nodejs.org/docs)
- [Express.js Guide](https://expressjs.com/en/guide/routing.html)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [MongoDB Documentation](https://docs.mongodb.com/)

---

**Happy Coding! 🚀**