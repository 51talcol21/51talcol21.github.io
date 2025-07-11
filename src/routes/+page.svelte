<script lang="ts">
    var jumpscare: boolean = false;
</script>

{#if jumpscare}
<div class="fixed inset-0 bg-gray-900/50 flex items-center justify-center">
    <div class="bg-white opacity-100 p-6 rounded-lg shadow-lg flex-col">
        <button on:click={()=> jumpscare = false} class="w-full mx-auto cursor-pointer border-amber-700 border-2"> CLOSE THIS JUMPSCARE PLEASE!!!! x</button>
        <h1 class="mx-auto"> jumpscared heheeh!!! </h1>
        <span class="text-9xl"> ¯\_(ツ)_/¯ </span>
    </div>
  </div>
{/if}

<div>
    <div class="flex flex-col items-center gap-2">
        <h1 class="font-bold text-3xl">
            Hi! Welcome to my website!
        </h1>
        <h1 class="font-semibold text-2xl">
            I'm Thaddeus. Kinda barebones right now while I work on it.
        </h1>
    
        <p>
            Created using 
            <a href="https://svelte.dev/docs/kit">Svelte</a>
                and styled using 
            <span class="italic"> 
                Tailwind
            </span>
        </p>
    </div>
    
    <hr class="h-px my-8 bg-gray-200 border-0 dark:bg-gray-700 max-w-4xl mx-auto">
    
    <div class="flex flex-col mx-auto max-w-3xl gap-4">
        <p class="max-w-3xl mx-auto">
            Hey! A little about me. I'm Thaddeus Lipke, and I graduated from Columbia University in the City of New York in 2022 with a major in Computer Science.
            I work SWE and helped found <a href="https://earthforce.app" class="text-blue-600 hover:text-green-500 hover:transition-colors transition duration-300 ease-in-out">earthforce</a> as a founding software engineer.
            I also interned at <a href="https://markforged.com/" class="text-blue-600 hover:text-green-500 hover:transition-colors transition duration-300 ease-in-out">Markforged</a> to do software engineering.
        </p>
    
        <p>
            Have lots of various projects. I was on Columbia University's game dev as served on the board, and helped with a few games. 
            At the university of Wyoming, I worked with Patrick Kelley lab at UWyo and helped with ML being used to identify a bird species' age by spectrogram. Using Keras and Python.
            I also did data annotation for the Tarwater Lab and Chalfoun Lab, serving as a Research Assistant in both. 
        </p>
    
        <p> My hobbies/interests are currently in bio-informatics, game development, activism, mutual aid, and doomscrolling. 
                <span 
                    on:mouseenter={() => jumpscare = true} 
                    class="hover:text-9xl"> ¯\_(ツ)_/¯ </span> </p>
    
        <p> I'm also EMT-B certified nationally and helped tutor courses at Pima Community College for the EMT program.</p>
    
        <p> I help with volunteer groups and mutual aid, helping to ensure immediate harm reduction for all people. </p>
    </div>
</div>
