<template>
    <div>
        <!-- SIDEBAR -->
        <div class="sidebar-menu hidden-xs hidden-sm">
            <div class="top-section">
                <div class="profile-image">
                    <img src="../assets/img/profile.jpg" alt="Profile">
                </div>
                <h3 class="profile-title">Gustavo Freitas</h3>
                <p class="profile-description">PHP Web Software Developer</p>
            </div> <!-- top-section -->
            <div class="main-navigation" style="margin-top:0px;">
                <ul class="navigation">
                    <li><a href="#top"><i class="fa fa-globe"></i>Welcome</a></li>
                    <li><a href="#about"><i class="fa fa-pencil"></i>About Me</a></li>
                    <li><a href="#projects"><i class="fa fa-paperclip"></i>My Projects</a></li>
                    <li><a href="#education"><i class="fa fa-book"></i>Education</a></li>
                    <li><a href="#references"><i class="fa fa-share-alt"></i>References</a></li>
                    <li><a href="#contact"><i class="fa fa-link"></i>Contact Me</a></li>
                </ul>
            </div> <!-- .main-navigation -->
            <div class="social-icons">
                <ul>
                    <li><a href="mailto:ac.gbpf@gmail.com"><i class="fa fa-envelope"></i></a></li>
                    <li><a href="https://linkedin.com/in/gustavobpf"><i class="fa fa-linkedin"></i></a></li>
                    <li><a href="https://github.com/ac-gbpfreitas"><i class="fa fa-github"></i></a></li>
                </ul>
            </div> <!-- .social-icons -->
        </div> <!-- .sidebar-menu -->
    </div>
</template>

<script>

export default {
    name: 'LeftMenu',
    props: {
        msg: String
    }
}
</script>

<style scoped>

</style>