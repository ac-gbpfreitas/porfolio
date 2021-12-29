<template>
    <div class="main-content">
        <div class="fluid-container">
            <div class="content-wrapper">

                <!-- ABOUT -->
                <div class="page-section" id="about">
                    <div class="row">
                        <About/>    
                    </div>
                </div>
                <hr>

                <!-- PROJECTS -->
                <div class="page-section" id="projects">
                    <div class="row">
                        <div class="col-md-12">
                            <h4 class="widget-title">Few Labs and Projects</h4>
                        </div>
                        <Projects/>    
                    </div>
                </div>
                <hr>

                <!-- EDUCATION -->
                <div class="page-section" id="education">
                    <div class="row">
                        <Education/>    
                    </div>
                </div>
                <hr>

                <!-- REFERENCES -->
                <div class="page-section" id="references">
                    <div class="row">
                        <References/>    
                    </div>
                </div>
                <hr>

                <!-- CONTACT -->
                <div class="page-section" id="contact">
                    <div class="row">
                        <Contact/>    
                    </div>
                </div>
                <hr>
                
            </div>
        </div>
    </div>
</template>

<script>
import About from './About.vue';
import Projects from './Projects.vue';
import Education from './Education.vue';
import References from './Referecences.vue';
import Contact from './Contact.vue';


export default {
    name: 'MainContent',
    components: {
        About,
        Projects,
        Education,
        References,
        Contact
    },
    props: {
        msg: String
    }
}
</script>
