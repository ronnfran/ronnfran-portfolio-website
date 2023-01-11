<script>
  import "../app.css";
  import Header from "./Header.svelte"
</script>

<div class="bg-gradient-to-t from-teal-300 to-red-300 py-5 grid place-items-center min-h-full">
  <div class="bg-blue-100 bg-opacity-50 shadow-lg rounded-2xl min-h-screen max-h-full lg:w-2/3 sm:w-2/3 ">
    <Header/>
  
    <main>
     <slot/>
    </main>
  
  
  </div>
</div>
