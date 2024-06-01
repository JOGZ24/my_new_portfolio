<script>
    import Project from "../../components/project.svelte";
</script>

<div class="introduction">
    <p>
        I have worked on many projects, some of them are my own and some of them
        are for clients, using different technologies and frameworks, from small
        to large scale projects. Check this portfolio here. Here are some of the
        projects that I have worked on.
    </p>
    <p>Here are some of the projects that I have worked on.</p>
</div>
<div class="projects">
    <Project
        image="https://imgs.search.brave.com/sgNnolKN2EOptHWyVbxMiRCjQFUcMXdlzjD9dHSs7I0/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM3/MDkyOTM3Ny9waG90/by9jbG9zZS11cC1v/Zi1jb21wdXRlci1w/cm9ncmFtbWVyLWNv/ZGluZy5qcGc_cz02/MTJ4NjEyJnc9MCZr/PTIwJmM9dmxvQkhr/d0I4azVfWUszTXRf/NUJvbG50VG1qUnFP/Z2tBSzUzMXlzM2hr/bz0"
    ></Project>
    <Project
        image="https://imgs.search.brave.com/sgNnolKN2EOptHWyVbxMiRCjQFUcMXdlzjD9dHSs7I0/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM3/MDkyOTM3Ny9waG90/by9jbG9zZS11cC1v/Zi1jb21wdXRlci1w/cm9ncmFtbWVyLWNv/ZGluZy5qcGc_cz02/MTJ4NjEyJnc9MCZr/PTIwJmM9dmxvQkhr/d0I4azVfWUszTXRf/NUJvbG50VG1qUnFP/Z2tBSzUzMXlzM2hr/bz0"
    ></Project>
    <Project
        image="https://imgs.search.brave.com/sgNnolKN2EOptHWyVbxMiRCjQFUcMXdlzjD9dHSs7I0/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM3/MDkyOTM3Ny9waG90/by9jbG9zZS11cC1v/Zi1jb21wdXRlci1w/cm9ncmFtbWVyLWNv/ZGluZy5qcGc_cz02/MTJ4NjEyJnc9MCZr/PTIwJmM9dmxvQkhr/d0I4azVfWUszTXRf/NUJvbG50VG1qUnFP/Z2tBSzUzMXlzM2hr/bz0"
    ></Project>
    <Project
        image="https://imgs.search.brave.com/sgNnolKN2EOptHWyVbxMiRCjQFUcMXdlzjD9dHSs7I0/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM3/MDkyOTM3Ny9waG90/by9jbG9zZS11cC1v/Zi1jb21wdXRlci1w/cm9ncmFtbWVyLWNv/ZGluZy5qcGc_cz02/MTJ4NjEyJnc9MCZr/PTIwJmM9dmxvQkhr/d0I4azVfWUszTXRf/NUJvbG50VG1qUnFP/Z2tBSzUzMXlzM2hr/bz0"
    ></Project>
    <Project
        image="https://imgs.search.brave.com/sgNnolKN2EOptHWyVbxMiRCjQFUcMXdlzjD9dHSs7I0/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM3/MDkyOTM3Ny9waG90/by9jbG9zZS11cC1v/Zi1jb21wdXRlci1w/cm9ncmFtbWVyLWNv/ZGluZy5qcGc_cz02/MTJ4NjEyJnc9MCZr/PTIwJmM9dmxvQkhr/d0I4azVfWUszTXRf/NUJvbG50VG1qUnFP/Z2tBSzUzMXlzM2hr/bz0"
    ></Project>
    <Project
        image="https://imgs.search.brave.com/sgNnolKN2EOptHWyVbxMiRCjQFUcMXdlzjD9dHSs7I0/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM3/MDkyOTM3Ny9waG90/by9jbG9zZS11cC1v/Zi1jb21wdXRlci1w/cm9ncmFtbWVyLWNv/ZGluZy5qcGc_cz02/MTJ4NjEyJnc9MCZr/PTIwJmM9dmxvQkhr/d0I4azVfWUszTXRf/NUJvbG50VG1qUnFP/Z2tBSzUzMXlzM2hr/bz0"
    ></Project>
</div>
<div class="conclusion">
    <p>
        I have worked on many other projects, but I am not indexing them here
        because they are not public or I don't have the permission to share
        them.
    </p>
</div>

<style>
    .conclusion {
        width: 60vw;
        margin-top: 40px;
    }
    .introduction {
        width: 60vw;

        font-size: 1.1em;
        display: flex;
        flex-direction: column;
    }

    .projects {
        width: 60vw;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
    }
</style>
