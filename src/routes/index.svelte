
<script>
    import Navbar from '../navbar.svelte'
</script>

<main>
    <section>
        <div class="container mx-auto flex justify-center">
            <button class="text-3xl font-light bg-red-500 hover:bg-red-400
                  active:transform active:translate-y-2 shadow-md
                  p-3 my-4 rounded-2xl transition-all">Hello world!
            </button>
        </div>
        <Navbar/>
    </section>

    <section class="bg-black ">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-1">
            <div class="bg-white m-4 p-4 rounded flex flex-col flex-wrap justify-center">
                <div>
                    <h3>sdasd</h3>
                </div>
                <div class="bg-red-300 mt-2 rounded flex justify-center">
                    <div class="collapse border rounded-box border-base-300 collapse-arrow">
                        <input type="checkbox"> 
                        <div class="collapse-title text-xl font-medium">
                          I open/close with click
                        </div> 
                        <div class="collapse-content"> 
                          <p>Collapse content reveals with focus. If you add a checkbox, you can control it using checkbox instead of focus. Or you can force-open/force-close using 
                            <span class="badge badge-outline">collapse-open</span> and 
                            <span class="badge badge-outline">collapse-close</span> classes.
                          </p>
                        </div>
                      </div>
                </div>
            </div>
            <div class="bg-white m-4 p-4 rounded flex flex-col justify-center">
                <div>
                    <h3>sdasd</h3>
                </div>
                <div class="bg-red-700 mt-2 rounded">
                    sdljf
                </div>
            </div>
            <div class="bg-white m-4 p-4 rounded flex flex-col justify-center">
                <div>
                    <h3>sdasd</h3>
                </div>
                <div class="bg-red-700 mt-2 rounded flex justify-center">
                    <button
                    class="inline-block px-4 py-3 text-sm font-semibold
                     text-center text-white uppercase transition 
                     duration-200 ease-in-out bg-indigo-500 rounded-md 
                     cursor-pointer hover:bg-indigo-600">Tailwind
                    Button</button>
                </div>
            </div>
            <div class="bg-white m-4 p-4 rounded flex flex-col justify-center">
                <div>
                    <h3>sdasd</h3>
                </div>
                <div class="bg-red-700 mt-2 rounded">
                    <div tabindex="0" class="collapse ">
                        <input type="checkbox"> 
                        <div class="collapse-title text-xl font-medium">
                            I open with focus
                        </div>
                        <div class="collapse-content">
                            <p>Collapse content reveals with focus. If you add a checkbox, you can control it using checkbox
                                instead of focus. Or you can force-open/force-close using
                                <span class="badge badge-outline">collapse-open</span> and
                                <span class="badge badge-outline">collapse-close</span> classes.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="grid grid-cols-4">
            <div>dsfsd</div>
            <div>dsfsd</div>


        </div>
    </section>
</main>