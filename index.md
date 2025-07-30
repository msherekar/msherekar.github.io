---
layout: custom
title: Home
---

<!-- Hero Section -->
<section class="hero" id="home" style="min-height: 100vh; display: flex; align-items: center; justify-content: center; text-align: center; padding: 0 5%; position: relative;">
    <div class="hero-content" style="max-width: 800px; animation: fadeInUp 1s ease-out;">
        <div class="hero-image" style="width: 200px; height: 200px; border-radius: 50%; margin: 0 auto 2rem; border: 4px solid transparent; background: linear-gradient(45deg, #22c55e, #3b82f6); padding: 4px; position: relative; overflow: hidden;">
            <img src="{{ site.baseurl }}/assets/images/Profile_Buenos_Aires.jpg" alt="Mukul Sherekar" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover; background: #1e293b;" onerror="this.style.display='none'">
        </div>
        <h1 class="hero-title" style="font-size: clamp(2.5rem, 5vw, 4rem); font-weight: 800; margin-bottom: 1rem; background: linear-gradient(45deg, #ffffff, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Mukul Sherekar</h1>
        <p class="hero-subtitle" style="font-size: 1.5rem; color: #94a3b8; margin-bottom: 2rem;">Bridging Biology & Artificial Intelligence</p>
        <div class="bilingual-tag" style="display: inline-block; background: linear-gradient(45deg, rgba(34, 197, 94, 0.2), rgba(59, 130, 246, 0.2)); border: 1px solid rgba(34, 197, 94, 0.3); padding: 0.5rem 1.5rem; border-radius: 50px; font-size: 1.1rem; margin: 1rem 0; backdrop-filter: blur(10px);">
            🧬 Bilingual in AI × Biology 🤖
        </div>
        <p style="max-width: 600px; margin: 2rem auto; color: #94a3b8; font-size: 1.1rem;">
            Combining computational intelligence with biological insights to unlock new possibilities in research and innovation.
        </p>
    </div>
    <div class="scroll-indicator" style="position: absolute; bottom: 2rem; left: 50%; transform: translateX(-50%); animation: bounce 2s infinite;">
        <div style="color: #22c55e; font-size: 2rem;">↓</div>
    </div>
</section>

<!-- Skills Section -->
<section class="skills-section" id="skills" style="padding: 5rem 5%; max-width: 1200px; margin: 0 auto;">
    <h2 class="section-title" style="text-align: center; font-size: 2.5rem; font-weight: 700; margin-bottom: 3rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Dual Expertise</h2>
    <div class="skills-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 2rem;">
        <div class="skill-card fade-in-up" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 2rem; transition: all 0.3s ease; position: relative; overflow: hidden;">
            <span class="skill-icon bio-icon" style="font-size: 3rem; margin-bottom: 1rem; display: block; color: #22c55e;">🧬</span>
            <h3 class="skill-title" style="font-size: 1.3rem; font-weight: 600; margin-bottom: 1rem; color: #f1f5f9;">Biochemistry & Biology</h3>
            <p class="skill-description" style="color: #94a3b8; line-height: 1.6;">
                Deep understanding of molecular mechanisms, protein structures, cellular processes, and biological systems. Expertise in laboratory techniques, molecular biology protocols, and experimental design.
            </p>
        </div>
        <div class="skill-card fade-in-up" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 2rem; transition: all 0.3s ease; position: relative; overflow: hidden;">
            <span class="skill-icon ai-icon" style="font-size: 3rem; margin-bottom: 1rem; display: block; color: #3b82f6;">🤖</span>
            <h3 class="skill-title" style="font-size: 1.3rem; font-weight: 600; margin-bottom: 1rem; color: #f1f5f9;">Artificial Intelligence</h3>
            <p class="skill-description" style="color: #94a3b8; line-height: 1.6;">
                Advanced machine learning, deep learning, and data analysis. Proficient in Python, R, bioinformatics tools, and developing AI solutions for complex biological problems.
            </p>
        </div>
        <div class="skill-card fade-in-up" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 2rem; transition: all 0.3s ease; position: relative; overflow: hidden;">
            <span class="skill-icon bridge-icon" style="font-size: 3rem; margin-bottom: 1rem; display: block; color: #f59e0b;">🌉</span>
            <h3 class="skill-title" style="font-size: 1.3rem; font-weight: 600; margin-bottom: 1rem; color: #f1f5f9;">Interdisciplinary Innovation</h3>
            <p class="skill-description" style="color: #94a3b8; line-height: 1.6;">
                Unique ability to translate between biological concepts and computational approaches, creating novel solutions at the intersection of life sciences and technology.
            </p>
        </div>
    </div>
</section>

<!-- Projects Preview -->
<section class="projects-preview" id="projects" style="padding: 5rem 5%; background: rgba(15, 23, 42, 0.5);">
    <div style="max-width: 1200px; margin: 0 auto;">
        <h2 class="section-title" style="text-align: center; font-size: 2.5rem; font-weight: 700; margin-bottom: 3rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Featured Work</h2>
        <div class="projects-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 2rem; max-width: 1200px; margin: 2rem auto 0;">
            <div class="project-card" style="background: rgba(30, 41, 59, 0.8); border-radius: 15px; overflow: hidden; transition: all 0.3s ease; border: 1px solid rgba(59, 130, 246, 0.2);">
                <div class="project-image" style="height: 200px; background: linear-gradient(135deg, #22c55e, #3b82f6); display: flex; align-items: center; justify-content: center; font-size: 3rem; color: white;">🧪</div>
                <div class="project-content" style="padding: 1.5rem;">
                    <h3 class="project-title" style="font-size: 1.2rem; font-weight: 600; margin-bottom: 0.5rem; color: #f1f5f9;">Computational Biology Research</h3>
                    <p class="project-description" style="color: #94a3b8; font-size: 0.9rem;">
                        Applying machine learning to predict protein folding patterns and drug-target interactions.
                    </p>
                </div>
            </div>
            <div class="project-card" style="background: rgba(30, 41, 59, 0.8); border-radius: 15px; overflow: hidden; transition: all 0.3s ease; border: 1px solid rgba(59, 130, 246, 0.2);">
                <div class="project-image" style="height: 200px; background: linear-gradient(135deg, #22c55e, #3b82f6); display: flex; align-items: center; justify-content: center; font-size: 3rem; color: white;">📊</div>
                <div class="project-content" style="padding: 1.5rem;">
                    <h3 class="project-title" style="font-size: 1.2rem; font-weight: 600; margin-bottom: 0.5rem; color: #f1f5f9;">Bioinformatics Pipeline</h3>
                    <p class="project-description" style="color: #94a3b8; font-size: 0.9rem;">
                        Automated analysis workflows for genomic data processing and variant identification.
                    </p>
                </div>
            </div>
            <div class="project-card" style="background: rgba(30, 41, 59, 0.8); border-radius: 15px; overflow: hidden; transition: all 0.3s ease; border: 1px solid rgba(59, 130, 246, 0.2);">
                <div class="project-image" style="height: 200px; background: linear-gradient(135deg, #22c55e, #3b82f6); display: flex; align-items: center; justify-content: center; font-size: 3rem; color: white;">🔬</div>
                <div class="project-content" style="padding: 1.5rem;">
                    <h3 class="project-title" style="font-size: 1.2rem; font-weight: 600; margin-bottom: 0.5rem; color: #f1f5f9;">AI-Driven Drug Discovery</h3>
                    <p class="project-description" style="color: #94a3b8; font-size: 0.9rem;">
                        Neural networks for molecular property prediction and compound optimization.
                    </p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section class="contact-section" id="contact" style="padding: 5rem 5%; text-align: center;">
    <h2 class="section-title" style="text-align: center; font-size: 2.5rem; font-weight: 700; margin-bottom: 3rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Let's Connect</h2>
    <p style="max-width: 600px; margin: 0 auto; color: #94a3b8; font-size: 1.1rem;">
        Interested in collaborating on projects that bridge AI and biology? Let's discuss how we can work together.
    </p>
    <div class="contact-links" style="display: flex; justify-content: center; gap: 2rem; margin-top: 2rem; flex-wrap: wrap;">
        <a href="mailto:mukulsherekar@gmail.com" class="contact-link" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 1rem 2rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px);">
            📧 Email
        </a>
        <a href="https://github.com/msherekar" class="contact-link" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 1rem 2rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px);">
            💻 GitHub
        </a>
        <a href="https://linkedin.com/in/mukulsherekar" class="contact-link" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 1rem 2rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px);">
            💼 LinkedIn
        </a>
        <a href="https://medium.com/me/stories/public" class="contact-link" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 1rem 2rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px);">
            ✍️ Blog
        </a>
    </div>
</section>

<style>
/* Additional styles for hover effects */
.skill-card:hover {
    transform: translateY(-10px);
    border-color: rgba(34, 197, 94, 0.4);
    box-shadow: 0 20px 40px rgba(34, 197, 94, 0.1);
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 30px rgba(59, 130, 246, 0.2);
}

.contact-link:hover {
    background: rgba(34, 197, 94, 0.1);
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(34, 197, 94, 0.2);
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

@media (max-width: 768px) {
    .contact-links {
        flex-direction: column;
        align-items: center;
    }
    
    .skills-grid {
        grid-template-columns: 1fr;
    }
}
</style>

