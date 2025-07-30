<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mukul Sherekar - AI × Biology Research</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            line-height: 1.6;
            color: #e2e8f0;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #334155 100%);
            overflow-x: hidden;
        }

        /* Animated background particles */
        .bg-particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .particle {
            position: absolute;
            width: 4px;
            height: 4px;
            background: rgba(34, 197, 94, 0.3);
            border-radius: 50%;
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); opacity: 0.3; }
            50% { transform: translateY(-20px) rotate(180deg); opacity: 0.8; }
        }

        /* Header */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(15, 23, 42, 0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            transition: all 0.3s ease;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            background: linear-gradient(45deg, #22c55e, #3b82f6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            color: #e2e8f0;
            text-decoration: none;
            transition: all 0.3s ease;
            position: relative;
        }

        .nav-links a:hover {
            color: #22c55e;
            transform: translateY(-2px);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -5px;
            left: 0;
            background: linear-gradient(45deg, #22c55e, #3b82f6);
            transition: width 0.3s ease;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        /* Hero Section */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 0 5%;
            position: relative;
        }

        .hero-content {
            max-width: 800px;
            animation: fadeInUp 1s ease-out;
        }

        .hero-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin: 0 auto 2rem;
            border: 4px solid transparent;
            background: linear-gradient(45deg, #22c55e, #3b82f6);
            padding: 4px;
            position: relative;
            overflow: hidden;
        }

        .hero-image img {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover;
            background: #1e293b;
        }

        .hero-title {
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 800;
            margin-bottom: 1rem;
            background: linear-gradient(45deg, #ffffff, #22c55e, #3b82f6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero-subtitle {
            font-size: 1.5rem;
            color: #94a3b8;
            margin-bottom: 2rem;
        }

        .bilingual-tag {
            display: inline-block;
            background: linear-gradient(45deg, rgba(34, 197, 94, 0.2), rgba(59, 130, 246, 0.2));
            border: 1px solid rgba(34, 197, 94, 0.3);
            padding: 0.5rem 1.5rem;
            border-radius: 50px;
            font-size: 1.1rem;
            margin: 1rem 0;
            backdrop-filter: blur(10px);
        }

        /* Skills Section */
        .skills-section {
            padding: 5rem 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 3rem;
            background: linear-gradient(45deg, #22c55e, #3b82f6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .skill-card {
            background: rgba(30, 41, 59, 0.8);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(34, 197, 94, 0.2);
            border-radius: 20px;
            padding: 2rem;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .skill-card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(34, 197, 94, 0.1), transparent);
            transform: rotate(45deg);
            transition: all 0.6s ease;
            opacity: 0;
        }

        .skill-card:hover::before {
            opacity: 1;
            transform: rotate(45deg) translate(50%, 50%);
        }

        .skill-card:hover {
            transform: translateY(-10px);
            border-color: rgba(34, 197, 94, 0.4);
            box-shadow: 0 20px 40px rgba(34, 197, 94, 0.1);
        }

        .skill-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            display: block;
        }

        .bio-icon { color: #22c55e; }
        .ai-icon { color: #3b82f6; }
        .bridge-icon { color: #f59e0b; }

        .skill-title {
            font-size: 1.3rem;
            font-weight: 600;
            margin-bottom: 1rem;
            color: #f1f5f9;
        }

        .skill-description {
            color: #94a3b8;
            line-height: 1.6;
        }

        /* Projects Preview */
        .projects-preview {
            padding: 5rem 5%;
            background: rgba(15, 23, 42, 0.5);
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
            max-width: 1200px;
            margin: 2rem auto 0;
        }

        .project-card {
            background: rgba(30, 41, 59, 0.8);
            border-radius: 15px;
            overflow: hidden;
            transition: all 0.3s ease;
            border: 1px solid rgba(59, 130, 246, 0.2);
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(59, 130, 246, 0.2);
        }

        .project-image {
            height: 200px;
            background: linear-gradient(135deg, #22c55e, #3b82f6);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: white;
        }

        .project-content {
            padding: 1.5rem;
        }

        .project-title {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
            color: #f1f5f9;
        }

        .project-description {
            color: #94a3b8;
            font-size: 0.9rem;
        }

        /* Contact Section */
        .contact-section {
            padding: 5rem 5%;
            text-align: center;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }

        .contact-link {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 1rem 2rem;
            background: rgba(30, 41, 59, 0.8);
            border: 1px solid rgba(34, 197, 94, 0.3);
            border-radius: 50px;
            color: #e2e8f0;
            text-decoration: none;
            transition: all 0.3s ease;
            backdrop-filter: blur(10px);
        }

        .contact-link:hover {
            background: rgba(34, 197, 94, 0.1);
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(34, 197, 94, 0.2);
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .fade-in-up {
            animation: fadeInUp 0.8s ease-out;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero-title {
                font-size: 2.5rem;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }

        /* Scroll indicator */
        .scroll-indicator {
            position: absolute;
            bottom: 2rem;
            left: 50%;
            transform: translateX(-50%);
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateX(-50%) translateY(0);
            }
            40% {
                transform: translateX(-50%) translateY(-10px);
            }
            60% {
                transform: translateX(-50%) translateY(-5px);
            }
        }
    </style>
</head>
<body>
    <!-- Animated background -->
    <div class="bg-particles" id="particles"></div>

    <!-- Header -->
    <header>
        <nav>
            <div class="logo">MS</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <div class="hero-image">
                <img src="assets/images/Profile_Buenos_Aires.jpg" alt="Mukul Sherekar" onerror="this.style.display='none'">
            </div>
            <h1 class="hero-title">Mukul Sherekar</h1>
            <p class="hero-subtitle">Bridging Biology & Artificial Intelligence</p>
            <div class="bilingual-tag">
                🧬 Bilingual in AI × Biology 🤖
            </div>
            <p style="max-width: 600px; margin: 2rem auto; color: #94a3b8; font-size: 1.1rem;">
                Combining computational intelligence with biological insights to unlock new possibilities in research and innovation.
            </p>
        </div>
        <div class="scroll-indicator">
            <div style="color: #22c55e; font-size: 2rem;">↓</div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="skills-section" id="skills">
        <h2 class="section-title">Dual Expertise</h2>
        <div class="skills-grid">
            <div class="skill-card fade-in-up">
                <span class="skill-icon bio-icon">🧬</span>
                <h3 class="skill-title">Biochemistry & Biology</h3>
                <p class="skill-description">
                    Deep understanding of molecular mechanisms, protein structures, cellular processes, and biological systems. Expertise in laboratory techniques, molecular biology protocols, and experimental design.
                </p>
            </div>
            <div class="skill-card fade-in-up">
                <span class="skill-icon ai-icon">🤖</span>
                <h3 class="skill-title">Artificial Intelligence</h3>
                <p class="skill-description">
                    Advanced machine learning, deep learning, and data analysis. Proficient in Python, R, bioinformatics tools, and developing AI solutions for complex biological problems.
                </p>
            </div>
            <div class="skill-card fade-in-up">
                <span class="skill-icon bridge-icon">🌉</span>
                <h3 class="skill-title">Interdisciplinary Innovation</h3>
                <p class="skill-description">
                    Unique ability to translate between biological concepts and computational approaches, creating novel solutions at the intersection of life sciences and technology.
                </p>
            </div>
        </div>
    </section>

    <!-- Projects Preview -->
    <section class="projects-preview" id="projects">
        <div style="max-width: 1200px; margin: 0 auto;">
            <h2 class="section-title">Featured Work</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">🧪</div>
                    <div class="project-content">
                        <h3 class="project-title">Computational Biology Research</h3>
                        <p class="project-description">
                            Applying machine learning to predict protein folding patterns and drug-target interactions.
                        </p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">📊</div>
                    <div class="project-content">
                        <h3 class="project-title">Bioinformatics Pipeline</h3>
                        <p class="project-description">
                            Automated analysis workflows for genomic data processing and variant identification.
                        </p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">🔬</div>
                    <div class="project-content">
                        <h3 class="project-title">AI-Driven Drug Discovery</h3>
                        <p class="project-description">
                            Neural networks for molecular property prediction and compound optimization.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact-section" id="contact">
        <h2 class="section-title">Let's Connect</h2>
        <p style="max-width: 600px; margin: 0 auto; color: #94a3b8; font-size: 1.1rem;">
            Interested in collaborating on projects that bridge AI and biology? Let's discuss how we can work together.
        </p>
        <div class="contact-links">
            <a href="mailto:mukulsherekar@gmail.com" class="contact-link">
                📧 Email
            </a>
            <a href="https://github.com/msherekar" class="contact-link" target="_blank">
                💻 GitHub
            </a>
            <a href="https://linkedin.com/in/mukulsherekar" class="contact-link" target="_blank">
                💼 LinkedIn
            </a>
            <a href="https://medium.com/me/stories/public" class="contact-link" target="_blank">
                ✍️ Blog
            </a>
        </div>
    </section>

    <script>
        // Create animated background particles
        function createParticles() {
            const container = document.getElementById('particles');
            const particleCount = 50;
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.className = 'particle';
                particle.style.left = Math.random() * 100 + '%';
                particle.style.top = Math.random() * 100 + '%';
                particle.style.animationDelay = Math.random() * 6 + 's';
                particle.style.animationDuration = (Math.random() * 3 + 3) + 's';
                container.appendChild(particle);
            }
        }

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Header scroll effect
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.style.background = 'rgba(15, 23, 42, 0.98)';
            } else {
                header.style.background = 'rgba(15, 23, 42, 0.95)';
            }
        });

        // Intersection Observer for animations
        const observeElements = document.querySelectorAll('.skill-card');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        });

        observeElements.forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'all 0.8s ease';
            observer.observe(el);
        });

        // Initialize particles
        createParticles();
    </script>
</body>
</html>