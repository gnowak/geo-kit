<script>
    import { onMount } from 'svelte';
    
    let message = "Loading...";
  
    onMount(async () => {
      message = "Welcome to the Geo-Kit Stack!";
    });
  </script>
  
  <div class="min-h-screen flex items-center justify-center bg-gray-900 text-white">
    <div class="p-4 shadow-lg rounded-lg bg-gray-800">
      <h1 class="text-4xl font-bold">{message}</h1>
      <p class="mt-2">
        This is a versatile tech stack template project that leverages the power of modern web development tools.
        Here's what you'll find inside:
      </p>
      <ul class="list-disc list-inside mt-2">
        <li>Svelte Kit, a powerful framework for building web applications with Svelte.</li>
        <li>Tailwind CSS, a utility-first CSS framework for rapidly building custom designs.</li>
        <li>TypeScript, a typed superset of JavaScript that brings static types and powerful tooling.</li>
        <li>Vite, a next-generation front-end build tool that offers fast and lean development experience.</li>
        <li>Jest, a delightful JavaScript Testing Framework with a focus on simplicity.</li>
        <li>Firebase, a comprehensive app development platform.</li>
        <li>And several other utilities like Prettier for code formatting, and Testing Library for robust testing.</li>
      </ul>
      <p class="mt-2">
        Feel free to explore the code, learn from it, and use it as a base for your own projects. Happy coding!
      </p>
    </div>
  </div>
  