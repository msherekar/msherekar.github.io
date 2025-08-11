---
layout: custom
title: Home
---

<!-- Main Layout Container -->
<div class="main-layout" style="display: grid; grid-template-columns: 1fr 1fr 1fr; grid-template-rows: auto auto; gap: 2rem; width: 100%; padding: 2rem 2%; min-height: 100vh; align-items: start;">

    <!-- Hero Section (Top Left) -->
    <section class="hero" id="home" style="display: flex; align-items: flex-start; justify-content: flex-start; position: relative;">
        <div class="hero-content" style="width: 100%; display: flex; flex-direction: column; align-items: flex-start; gap: 1.5rem; animation: fadeInUp 1s ease-out;">
            <!-- Image at top -->
            <div class="hero-image-container" style="align-self: flex-start;">
                <div class="hero-image" style="width: 200px; height: 200px; border-radius: 50%; border: 4px solid transparent; background: linear-gradient(45deg, #22c55e, #3b82f6); padding: 4px; position: relative; overflow: hidden;">
                    <img src="{{ site.baseurl }}/assets/images/Profile_Buenos_Aires.jpg" alt="Mukul Sherekar" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover; background: #1e293b;" onerror="this.style.display='none'">
                </div>
            </div>
            
            <!-- Text content below image -->
            <div class="hero-text" style="text-align: left; width: 100%;">
                <h1 class="hero-title" style="font-size: clamp(1.8rem, 3vw, 2.5rem); font-weight: 800; margin-bottom: 0.8rem; background: linear-gradient(45deg, #ffffff, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Mukul Sherekar</h1>
                <div class="bilingual-tag" style="display: inline-block; background: linear-gradient(45deg, rgba(34, 197, 94, 0.2), rgba(59, 130, 246, 0.2)); border: 1px solid rgba(34, 197, 94, 0.3); padding: 0.4rem 1rem; border-radius: 50px; font-size: 0.9rem; margin-bottom: 1rem; backdrop-filter: blur(10px);">
                    Bilingual in AI × Biology
                </div>
                <p style="color: #94a3b8; font-size: 0.9rem; line-height: 1.5;">
                    Interested in applying deep learning to protein designing and omics problems.
                </p>
            </div>
        </div>
    </section>

    <!-- About Me Section (Top Center) -->
    <div class="section-card" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 1.8rem;">
        <h2 style="color: #f1f5f9; font-size: 1.3rem; margin-bottom: 1rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">About Me</h2>
        <p style="color: #94a3b8; line-height: 1.5; margin-bottom: 1rem; font-size: 0.9rem;">
            I have an unique ability to bridge the gap between biological research and artificial intelligence. My journey began with a strong foundation in biotechnology, followed by 14 years of working as a protein biochemist and then training in bioinformatics and machine learning.
        </p>

    </div>

    <!-- Technical Skills Section (Top Right)
    <div class="section-card" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 1.8rem;">
        <h2 style="color: #f1f5f9; font-size: 1.3rem; margin-bottom: 1.2rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Technical Skills</h2>
        <div class="skills-list">
            <div class="skill-category" style="margin-bottom: 1.2rem;">
                <h3 style="color: #22c55e; font-size: 1rem; margin-bottom: 0.4rem;">🧬 Bioinformatics</h3>
                <p style="color: #94a3b8; font-size: 0.8rem; line-height: 1.4;">RNA-Seq, ATAC-Seq, scRNA-seq, BLAST, ENSEMBL, UCSC Genome Browser, DNA/ProteinBERT</p>
            </div>
            <div class="skill-category" style="margin-bottom: 1.2rem;">
                <h3 style="color: #3b82f6; font-size: 1rem; margin-bottom: 0.4rem;">🤖 Machine Learning & AI</h3>
                <p style="color: #94a3b8; font-size: 0.8rem; line-height: 1.4;">Transformers, CNN, GNN, Autoencoders, GAN, Diffusion Models, PyTorch, TensorFlow</p>
            </div>
            <div class="skill-category" style="margin-bottom: 1rem;">
                <h3 style="color: #f59e0b; font-size: 1rem; margin-bottom: 0.4rem;">💻 Programming & Tools</h3>
                <p style="color: #94a3b8; font-size: 0.8rem; line-height: 1.4;">Python, R, Bash, Docker, AWS, SLURM, Snakemake, CI/CD, GitHub, MongoDB</p>
            </div>
        </div>
    </div> -->

    <!-- Experience Section (Bottom Left) -->


    <!-- Projects Section (Bottom Right) -->
    <div class="section-card" style="background: rgba(30, 41, 59, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(34, 197, 94, 0.2); border-radius: 20px; padding: 1.8rem;">
        <h2 style="color: #f1f5f9; font-size: 1.3rem; margin-bottom: 1.2rem; background: linear-gradient(45deg, #22c55e, #3b82f6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Projects</h2>
        <div class="project-item" style="margin-bottom: 1.2rem;">
            <h3 style="color: #f1f5f9; font-size: 1rem; margin-bottom: 0.3rem;">🧬 Virtual Cell Challenge</h3>
            <p style="color: #94a3b8; font-size: 0.8rem; line-height: 1.3;">Predict effects of perturbation in held out cell type. Translate scRNAseq data into graph embeddings.</p>
        </div>
        <div class="project-item" style="margin-bottom: 1.2rem;">
            <h3 style="color: #f1f5f9; font-size: 1rem; margin-bottom: 0.3rem;">🌐 Ecosystem: MCP</h3>
            <p style="color: #94a3b8; font-size: 0.8rem; line-height: 1.3;">Scalable MCP architecture for unified agent access and context awareness in analysis workflows.</p>
        </div>
        <div class="project-item" style="margin-bottom: 1rem;">
            <h3 style="color: #f1f5f9; font-size: 1rem; margin-bottom: 0.3rem;">🎓 Education</h3>
            <p style="color: #94a3b8; font-size: 0.8rem; line-height: 1.3;">MS Bioinformatics (Johns Hopkins), MBiot Biotechnology (Texas A&M), BTech Biotechnology (VIT)</p>
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
@media (max-width: 1200px) {
    .main-layout {
        grid-template-columns: 1fr 1fr;
        grid-template-rows: auto auto auto;
        gap: 1.5rem;
        padding: 2rem 2%;
    }
    
    .hero {
        grid-column: 1 / 3;
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
    
    /* Experience section spans both columns */
    .section-card[style*="grid-column: 1 / 3"] {
        grid-column: 1 / 3;
    }
}

@media (max-width: 768px) {
    .main-layout {
        grid-template-columns: 1fr;
        grid-template-rows: auto auto auto auto auto;
        padding: 1rem 2%;
        gap: 1.5rem;
    }
    
    .hero-content {
        gap: 1.5rem;
    }
    
    .hero-image {
        width: 180px !important;
        height: 180px !important;
    }
    
    .section-card {
        padding: 1.5rem;
    }
    
    /* Reset grid-column for mobile */
    .section-card[style*="grid-column: 1 / 3"] {
        grid-column: 1;
    }
    
    /* Experience section internal grid becomes single column on mobile */
    .section-card[style*="grid-column: 1 / 3"] > div[style*="grid-template-columns"] {
        display: block !important;
    }
    
    .experience-item {
        margin-bottom: 1.5rem;
    }
    
    .contact-links {
        flex-direction: column;
        align-items: center;
    }
}

/* Smooth scrolling for navigation */
html {
    scroll-behavior: smooth;
}
</style>

