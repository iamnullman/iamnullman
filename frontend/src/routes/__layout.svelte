<script>
  import "../app.css";
  import 'tippy.js/dist/tippy.css';
  import Footer from "../components/Footer/footer.svelte";
</script>
 <main class="overflow-y-hidden md:overflow-y-visible min-h-[calc(100vh-14px)] max-w-screen-lg p-5 w-full md:py-10 md:w-10/12 lg:py-1 lg:w-[800px] mx-auto transition-all duration-300">
<slot />
<Footer/>
</main>