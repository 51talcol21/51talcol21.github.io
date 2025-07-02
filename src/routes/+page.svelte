<script lang="ts">
    import { base } from '$app/paths';
</script>

<nav class="flex flex-row gap-2 justify-center my-8">
    <a href="{base}/" class="hover:text-yellow-500 hover:transition-colors transition duration-300 ease-in-out">Home</a> - 
    <a href="{base}/about" class="hover:text-yellow-500 hover:transition-colors transition duration-300 ease-in-out">About</a>
</nav>

<hr class="h-px my-8 bg-gray-200 border-0 dark:bg-gray-700">

<body>
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

        <p> I'm also EMT-B certified nationally and helped tutor courses at Pima Community College for the EMT program.</p>

        <p> I help with volunteer groups and mutual aid, helping to alleviate where our society has failed it's people.</p>
    </div>
</body>