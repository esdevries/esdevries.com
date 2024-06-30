<script>
    import linkedin_svg from '/svg_icons/linkedin.svg'
    import github_svg from '/svg_icons/github.svg' 
</script>



<div class="icons">
    <a href="https://github.com/esdevries" target="_blank"><img src={github_svg} alt="github_logo"></a>
    <a href="https://www.linkedin.com/in/erwin-de-vries-019227315/" target="_blank"><img src={linkedin_svg} alt="linkedin_logo"></a>
</div>

<a href="/license">License 2024</a>

<style>
    .icons {
        display: flex;
        gap: 1rem;
    }

    .icons > a {
        width: 2rem;
        transition: width 0.3s ease;
    }

    .icons > a:hover {
        width: 2.5rem;
    }


    a {
        text-decoration: none;
        font-weight: 500;
        color: white;
        transition: font-size 0.3s ease;
        padding: 0.3rem 0;
    }

    a:hover {
        font-size: large;
    }

</style>