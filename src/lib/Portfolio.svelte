<script>
    export let bio;
    export let projects;
  </script>
  
  <section class="bio">
    <div class="container">
      <h2>About Me</h2>
      <p>{bio}</p>
    </div>
    </section>
    
    <section class="projects">
      <div class="container">
        <h2>Projects</h2>
        <div class="project-grid">
          {#each projects as project}
            <div class="project-card">
              <div class="project-image">
                <img src={project.image} alt={project.title} />
              </div>
              <div class="project-content">
                <h3>{project.title}</h3>
                <p>{project.description}</p>
                <div class="tech-stack">
                  {#each project.technologies as tech}
                    <span class="tech-tag">{tech}</span>
                  {/each}
                </div>
                <a href={project.github} class="project-link" target="_blank" rel="noopener noreferrer">
                  View on GitHub
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                </a>
              </div>
            </div>
          {/each}
        </div>
      </div>
    </section>