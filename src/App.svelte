<script>
  // Import components
  import Portfolio from './lib/Portfolio.svelte';
  import Header from './lib/Header.svelte';
  import Footer from './lib/Footer.svelte';
  import './app.css';
  // Portfolio data
  const portfolioData = {
    name: "Raphael Miyoyo",
    title: "Fullstack Developer",
    bio: "Highly motivated Full Stack Software Engineer with 2+ years of experience crafting scalable and user-centric web applications. Proficient in JavaScript, React, Redux, Ruby on Rails, Laravel and PostgreSQL. Adept at both frontend and backend development. I ensure responsive design and seamless user experiences. Strong advocate for collaboration and mentorship. Proven track record of delivering high-quality solutions on time, having completed over 30 projects.",
    social: {
      github: "https://github.com/rmiyoyo",
      bitbucket: "https://bitbucket.org/miyoyo",
      linkedin: "https://linkedin.com/in/raphael-miyoyo",
      twitter: "https://x.com/r_miyoyo"
    },
    projects: [
      {
        title: "E-commerce Platform",
        description: "A full-featured e-commerce platform with user authentication, product management, and payments.",
        image: "/images/ecommerce.png",
        technologies: ["Svelte", "Node.js", "MongoDB", "Stripe"],
        github: "https://github.com/rmiyoyo/ecommerce"
      },
      {
        title: "Task Management App",
        description: "A collaborative task management application with real-time updates and team workspace features.",
        image: "/images/taskapp.png",
        technologies: ["React", "GraphQL", "PostgreSQL", "WebSockets"],
        github: "https://github.com/rmiyoyo/taskmanager"
      },
      {
        title: "Financial Dashboard",
        description: "An interactive dashboard for visualizing financial data with customizable widgets and reports.",
        image: "/images/dashboard.png",
        technologies: ["Vue.js", "Express", "D3.js", "MySQL"],
        github: "https://github.com/rmiyoyo/financial-dashboard"
      },
      {
        title: "Social Media Analytics Tool",
        description: "A tool for analyzing social media performance with sentiment analysis, engagement metrics, and trend tracking.",
        image: "/images/social-analytics.png",
        technologies: ["Python", "Django", "Elasticsearch", "Chart.js"],
        github: "https://github.com/rmiyoyo/social-analytics"
      },
      {
        title: "Online Learning Platform",
        description: "A platform for creating and managing online courses with video streaming, quizzes, subscriptions, and progress tracking.",
        image: "/images/learning-platform.png",
        technologies: ["Angular", "NestJS", "Firebase", "Stripe"],
        github: "https://github.com/rmiyoyo/learning-platform"
      },
      {
        title: "Health Tracker App",
        description: "A mobile app for tracking health metrics like steps, calories, and sleep patterns with integration to wearable devices.",
        image: "/images/health-tracker.png",
        technologies: ["Flutter", "Node.js", "MongoDB", "Google Fit API"],
        github: "https://github.com/rmiyoyo/health-tracker"
      }
    ]
  };
</script>

<main>
  <Header name={portfolioData.name} title={portfolioData.title} social={portfolioData.social} />
  <Portfolio bio={portfolioData.bio} projects={portfolioData.projects} />
  <Footer name={portfolioData.name} social={portfolioData.social} />
</main>
