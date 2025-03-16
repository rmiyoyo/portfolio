<script>
  export let name;
  export let social;
  
  const year = new Date().getFullYear();
</script>

<footer>
  <div class="container">
    <p>&copy; {year} {name}. All rights reserved.</p>
    <div class="social">
      <a href={social.github} target="_blank" rel="noopener noreferrer" aria-label="GitHub">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
      </a>
      <a href={social.bitbucket} target="_blank" rel="noopener noreferrer" aria-label="Bitbucket">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6.3 5.7c-.2 0-.3.2-.3.4l1.8 11c0 .3.3.5.5.5h7.8c.3 0 .5-.2.5-.4l1.8-11c0-.2-.1-.4-.3-.4H6.3z"></path><path d="M19.1 5.3H4.9c-.4 0-.7.4-.7.8l1.6 11.2c0 .6.5 1 1.1 1H17c.6 0 1.1-.5 1.1-1L19.8 6c.1-.4-.2-.7-.7-.7zM14.7 12H9.4l-.7-3.4h6.5l-.5 3.4z"></path></svg>
      </a>
      <a href={social.linkedin} target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
      </a>
      <a href={social.twitter} target="_blank" rel="noopener noreferrer" aria-label="Twitter/X">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 4s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6 2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4-.9-4.2 4-6.6 7-3.8 1.1 0 3-1.2 3-1.2z"></path></svg>
      </a>
    </div>
  </div>
</footer>