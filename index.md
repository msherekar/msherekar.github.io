---
layout: custom
title: Home
---

<!-- Main Layout Container -->
<div class="main-layout" style="display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; max-width: 1400px; margin: 0 auto; padding: 2rem 5%; min-height: 100vh; align-items: start;">

    <!-- Hero Section (Left Side) -->
    <section class="hero" id="home" style="display: flex; align-items: flex-start; justify-content: flex-start; position: relative;">
        <div class="hero-content" style="max-width: 500px; width: 100%; display: flex; flex-direction: column; align-items: flex-start; gap: 2rem; animation: fadeInUp 1s ease-out;">
            <!-- Image at top -->
            <div class="hero-image-container" style="align-self: flex-start;">
                <div class="hero-image" style="width: 250px; height: 250px; border-radius: 50%; border: 4px solid transparent; background: linear-gradient(45deg, #22c55e, #3b82f6); padding: 4px; position: relative; overflow: hidden;">
                    <img src="{{ site.baseurl }}/assets/images/Profile_Buenos_Aires.jpg" alt="Mukul Sherekar" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover; background: #1e293b;" onerror="this.style.display='none'">
                </div>
            </div>
            
            <!-- Text content below image -->
            <div class="hero-text" style="text-align: left; width: 100%;">
                <h1 class="hero-title" style="font-size: clamp(2rem, 4vw, 3rem); font-weight: 800; margin-bottom: 1rem; background: linear-gradient(45deg, #ffffff, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Mukul Sherekar</h1>
                <p class="hero-subtitle" style="font-size: 1.3rem; color: #94a3b8; margin-bottom: 1.5rem;">AI-Proficient Bioinformatician</p>
                <div class="bilingual-tag" style="display: inline-block; background: linear-gradient(45deg, rgba(34, 197, 94, 0.2), rgba(59, 130, 246, 0.2)); border: 1px solid rgba(34, 197, 94, 0.3); padding: 0.5rem 1.5rem; border-radius: 50px; font-size: 1rem; margin-bottom: 1.5rem; backdrop-filter: blur(10px);">
                    Bilingual in AI × Biology
                </div>
                <p style="color: #94a3b8; font-size: 1rem; line-height: 1.6;">
                    Problem-solver with strong foundation, diverse skill set and expertise in bioinformatics and AI tools. Adept at bidirectional translation between biological complexities and AI frameworks.
                </p>
            </div>
        </div>
    </section>

    <!-- Main Content (Right Side) -->
    <div class="content-column" style="display: flex; flex-direction: column; gap: 2rem;">
        
        <!-- About Me Section -->
        <div class="section-card" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 2rem;">
            <h2 style="color: #f1f5f9; font-size: 1.5rem; margin-bottom: 1rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">About Me</h2>
            <p style="color: #94a3b8; line-height: 1.6; margin-bottom: 1rem;">
                I'm a bioinformatician with a unique ability to bridge the gap between biological research and artificial intelligence. My journey began with a strong foundation in biotechnology, followed by specialized training in bioinformatics and machine learning.
            </p>
            <p style="color: #94a3b8; line-height: 1.6;">
                Currently working at X10e, I curate RNAseq datasets and train ML models to predict gene regulation. My experience includes developing pipelines for multi-omics data analysis and creating tools that help biologists and ML engineers communicate effectively.
            </p>
        </div>

        <!-- Skills Section -->
        <div class="section-card" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 2rem;">
            <h2 style="color: #f1f5f9; font-size: 1.5rem; margin-bottom: 1.5rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Technical Skills</h2>
            <div class="skills-list">
                <div class="skill-category" style="margin-bottom: 1.5rem;">
                    <h3 style="color: #22c55e; font-size: 1.1rem; margin-bottom: 0.5rem;">🧬 Bioinformatics & Genomics</h3>
                    <p style="color: #94a3b8; font-size: 0.9rem;">RNA-Seq, ATAC-Seq, scRNA-seq, BLAST, ENSEMBL, UCSC Genome Browser, DNA/ProteinBERT, AlphaFold, ProteinMPNN</p>
                </div>
                <div class="skill-category" style="margin-bottom: 1.5rem;">
                    <h3 style="color: #3b82f6; font-size: 1.1rem; margin-bottom: 0.5rem;">🤖 Machine Learning & AI</h3>
                    <p style="color: #94a3b8; font-size: 0.9rem;">Transformers, CNN, GNN, Autoencoders, GAN, Diffusion Models, LLM, PyTorch, TensorFlow, Scikit-Learn</p>
                </div>
                <div class="skill-category" style="margin-bottom: 1.5rem;">
                    <h3 style="color: #f59e0b; font-size: 1.1rem; margin-bottom: 0.5rem;">💻 Programming & Tools</h3>
                    <p style="color: #94a3b8; font-size: 0.9rem;">Python, R, Bash, Perl, Docker, AWS, SLURM, Snakemake, CI/CD, GitHub, MySQL, MongoDB, Biopython</p>
                </div>
            </div>
        </div>

        <!-- Experience Section -->
        <div class="section-card" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 2rem;">
            <h2 style="color: #f1f5f9; font-size: 1.5rem; margin-bottom: 1.5rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Experience</h2>
            <div class="experience-item" style="margin-bottom: 1.5rem;">
                <h3 style="color: #f1f5f9; font-size: 1.1rem; margin-bottom: 0.3rem;">Bioinformatics & ML Engineer</h3>
                <p style="color: #22c55e; font-size: 0.9rem; margin-bottom: 0.5rem;">X10e • 04/25 - Current</p>
                <ul style="color: #94a3b8; font-size: 0.85rem; line-height: 1.4; padding-left: 1rem;">
                    <li>Curate RNAseq datasets and train ML models</li>
                    <li>Build bioinformatic analysis tools</li>
                    <li>Bridge communication between biologists and ML engineers</li>
                </ul>
            </div>
            <div class="experience-item" style="margin-bottom: 1rem;">
                <h3 style="color: #f1f5f9; font-size: 1.1rem; margin-bottom: 0.3rem;">ORISE Research Fellow</h3>
                <p style="color: #22c55e; font-size: 0.9rem; margin-bottom: 0.5rem;">FDA • 07/24 - 12/24</p>
                <ul style="color: #94a3b8; font-size: 0.85rem; line-height: 1.4; padding-left: 1rem;">
                    <li>Engineered mammography data preprocessing pipelines</li>
                    <li>Designed transfer learning experiments with ConvNeXtV1</li>
                    <li>Optimized CNN models through hyperparameter tuning</li>
                </ul>
            </div>
        </div>

        <!-- Projects Section -->
        <div class="section-card" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 2rem;">
            <h2 style="color: #f1f5f9; font-size: 1.5rem; margin-bottom: 1.5rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Projects</h2>
            <div class="project-item" style="margin-bottom: 1.5rem;">
                <h3 style="color: #f1f5f9; font-size: 1.1rem; margin-bottom: 0.3rem;">🧬 Virtual Cell Challenge</h3>
                <p style="color: #94a3b8; font-size: 0.85rem; line-height: 1.4;">Predict effects of perturbation in held out cell type. Translate scRNAseq data into graph embeddings.</p>
            </div>
            <div class="project-item" style="margin-bottom: 1.5rem;">
                <h3 style="color: #f1f5f9; font-size: 1.1rem; margin-bottom: 0.3rem;">🌐 Ecosystem: Model Context Protocol</h3>
                <p style="color: #94a3b8; font-size: 0.85rem; line-height: 1.4;">Scalable MCP architecture for unified agent access and context awareness in analysis workflows.</p>
            </div>
            <div class="project-item" style="margin-bottom: 1rem;">
                <h3 style="color: #f1f5f9; font-size: 1.1rem; margin-bottom: 0.3rem;">🎓 Education</h3>
                <p style="color: #94a3b8; font-size: 0.85rem; line-height: 1.4;">MS Bioinformatics (Johns Hopkins), MBiot Biotechnology (Texas A&M), BTech Biotechnology (VIT)</p>
            </div>
        </div>
        
    </div>
    </div>
</div>

<!-- Contact Section -->
<section class="contact-section" id="contact" style="padding: 3rem 5%; text-align: center; background: rgba(15, 23, 42, 0.5);">
    <h2 class="section-title" style="text-align: center; font-size: 2rem; font-weight: 700; margin-bottom: 2rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Let's Connect</h2>
    <div class="contact-links" style="display: flex; justify-content: center; gap: 1.5rem; flex-wrap: wrap;">
        <a href="mailto:mukulsherekar@gmail.com" class="contact-link" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.8rem 1.5rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px); font-size: 0.9rem;">
            📧 Email
        </a>
        <a href="https://github.com/msherekar" class="contact-link" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.8rem 1.5rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px); font-size: 0.9rem;">
            💻 GitHub
        </a>
        <a href="https://linkedin.com/in/mukulsherekar" class="contact-link" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.8rem 1.5rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px); font-size: 0.9rem;">
            💼 LinkedIn
        </a>
        <a href="https://medium.com/me/stories/public" class="contact-link" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.8rem 1.5rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px); font-size: 0.9rem;">
            ✍️ Blog
        </a>
        <a href="{{ site.baseurl }}/assets/documents/Bioinformatics_07262025.pdf" class="contact-link" target="_blank" style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.8rem 1.5rem; background: rgba(30, 41, 59, 0.8); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 50px; color: #e2e8f0; text-decoration: none; transition: all 0.3s ease; backdrop-filter: blur(10px); font-size: 0.9rem;">
            📄 Resume
        </a>
    </div>
</section>

<style>
/* Hover effects */
.section-card {
    transition: all 0.3s ease;
}

.section-card:hover {
    transform: translateY(-5px);
    border-color: rgba(34, 197, 94, 0.4);
    box-shadow: 0 15px 30px rgba(34, 197, 94, 0.1);
}

.contact-link:hover {
    background: rgba(34, 197, 94, 0.1);
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(34, 197, 94, 0.2);
}

/* Responsive design */
@media (max-width: 1024px) {
    .main-layout {
        grid-template-columns: 1fr;
        gap: 2rem;
        padding: 2rem 3%;
    }
    
    .hero {
        text-align: center;
    }
    
    .hero-content {
        align-items: center;
        max-width: 600px;
        margin: 0 auto;
    }
    
    .hero-text {
        text-align: center !important;
    }
}

@media (max-width: 768px) {
    .main-layout {
        padding: 1rem 3%;
        gap: 1.5rem;
    }
    
    .hero-content {
        gap: 1.5rem;
    }
    
    .hero-image {
        width: 200px !important;
        height: 200px !important;
    }
    
    .contact-links {
        flex-direction: column;
        align-items: center;
    }
    
    .section-card {
        padding: 1.5rem;
    }
}

/* Smooth scrolling for navigation */
html {
    scroll-behavior: smooth;
}
</style>

