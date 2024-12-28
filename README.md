# Next.js Authentication Component

A modern, responsive authentication component built with Next.js and CSS Modules. Features a clean design with sign-in and sign-up functionality, social authentication options, and smooth transitions.

## Features

- Responsive design for desktop and mobile
- Animated form switching between sign-in and sign-up
- Social authentication integration (Google & Facebook)
- Modern UI with background images and overlays
- Built with Next.js Image optimization

## Setup

1. Clone the repository:
```bash
[git clone https://github.com/pamaljayasinghe/Web-Site-Login-and-Signup-Pages-Next.js.git]
```

2. Install dependencies:
```bash
npm install
```

3. Add required images to your public folder:
```
public/
  └── img/
      ├── logo.png
      ├── signinimg.jpg
      ├── signupimg.jpg
      ├── google.png
      └── facebook.png
```

4. Import and use the component:
```jsx
import AuthComponent from './components/AuthComponent';

export default function Page() {
  return <AuthComponent />;
}
```

## Technologies Used

- Next.js 14
- CSS Modules
- Next.js Image Component

## License

MIT

## Author

[Your Name]
