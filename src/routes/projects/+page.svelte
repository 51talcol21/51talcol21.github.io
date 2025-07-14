<script lang="ts">
    import type { PageData } from './$types';
    
    export let data: PageData;
</script>

<div class="flex flex-col max-w-3xl mx-auto gap-2">
    <h1 class="text-3xl text-center">
        Projects
    </h1>
    
    <p class="max-w-3xl mx-auto">
        <strong> Currently working on uploading all of my projects, but here are the recent ones! </strong>
    </p>

    <span>
        <a href="https://51talcol21.github.io/needleman-wunsch-visualizer/" 
        class="text-blue-600 hover:text-green-500 hover:transition-colors transition duration-300 ease-in-out">
        Needleman-Wunsch Algorithm Visualizer
        </a> - A website that visualizes the Needleman-Wunsch algorithm for DNA regulation. React/Typescript/Tailwind.
    </span>

    <span>
        <a href="https://51talcol21.github.io/long-read-rna-mouse-brownfat/" 
        class="text-blue-600 hover:text-green-500 hover:transition-colors transition duration-300 ease-in-out">
        Long Read RNA Sequence Project
        </a> - This project aims to analyze long-read RNA sequencing data derived from mouse brown adipose tissue
         to identify and quantify known and novel transcript isoforms using a basic bio-informatics data analysis 
         pipeline: QC → alignment → correction → collapsing → quantifying → analysis.
    </span>

    <span>
        <a href="https://cugamedev.itch.io/" 
        class="text-blue-600 hover:text-green-500 hover:transition-colors transition duration-300 ease-in-out">
        Various Game Dev projects
        </a> - Was on the board of directors for gamedev and worked on some stuff!
    </span>
</div>