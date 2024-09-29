# Alpha - Digital a11y

![Accessibility Icon](/public/images/accessibility-icon.png)

## About the Project

Alpha - Digital a11y is a React-based web application dedicated to educating and providing resources about digital accessibility. Our mission is to make the digital world more inclusive by offering clear, concise information on various aspects of accessibility.

## Features

- Responsive design using Material-UI components
- Dynamic content loading from Markdown files stored in a separate GitHub repository
- Information on key accessibility topics:
  - Web Accessibility Basics
  - Mobile Accessibility
  - Document Accessibility
  - Assistive Technologies

## Getting Started

### Prerequisites

- Node.js (v14 or later recommended)
- npm (comes with Node.js)
- GitHub account for content storage

### Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/alpha-digital-a11y.git
   ```

2. Navigate to the project directory
   ```
   cd alpha-digital-a11y
   ```

3. Install NPM packages
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your GitHub content repo information:
   ```
   REACT_APP_GITHUB_USERNAME=your-content-github-username
   REACT_APP_GITHUB_REPO=your-content-repo-name
   ```

5. Start the development server
   ```
   npm start
   ```

The application should now be running on [http://localhost:3000](http://localhost:3000).

## Project Structure

```
alpha-digital-a11y/
│
├── public/
│   ├── index.html
│   └── images/
│       ├── accessibility-icon.png
│       ├── web-accessibility.png
│       ├── mobile-accessibility.png
│       ├── document-accessibility.png
│       └── assistive-tech.png
│
├── src/
│   ├── App.js
│   ├── index.js
│   └── ... (other React components)
│
├── .env
├── package.json
└── README.md
```

## Content Management

Content (markdown files) is stored in a separate GitHub repository. To update content:

1. Navigate to the content repository: `https://github.com/your-content-github-username/your-content-repo-name`
2. Edit existing .md files or create new ones
3. Commit and push changes to the content repository
4. The main application will fetch the updated content on the next load

## Adding New Pages

To add a new page:

1. Add a new markdown file to the content repository
2. Update the navigation in `src/App.js` to include the new page

## Deployment

This project is set up to be deployed on GitHub Pages. To deploy:

1. Ensure your repository is set up for GitHub Pages in the Settings
2. Run the deployment script:
   ```
   npm run deploy
   ```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter) - email@example.com

Project Link: [https://github.com/yourusername/alpha-digital-a11y](https://github.com/yourusername/alpha-digital-a11y)

Content Repository: [https://github.com/your-content-github-username/your-content-repo-name](https://github.com/your-content-github-username/your-content-repo-name)

## Acknowledgements

- [React](https://reactjs.org/)
- [Material-UI](https://material-ui.com/)
- [React Router](https://reactrouter.com/)
- [React Markdown](https://github.com/remarkjs/react-markdown)