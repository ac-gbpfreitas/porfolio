<template>
    <div class="col-md-12">
        <h4 class="widget-title">About Me</h4>
        <p class="custom-font-size">
            I am PHP software developer graduated in Computer and Information Systems at Douglas College.
            I am proactive, independent and an innovation enthusiast. 
            My best experience was in Brazil, where I was trained and worked with other PHP developers.
            During this experience, I was able to develop websites with database operations.    
        </p>
        <div style="float:left; width: 100%;">
                <div class="custom-skills">
                    <ul class="list-group">
                        <li class="list-group-item active">
                            Backend
                            <span class="badge badge-primary badge-pill"><i class="fa fa-code"></i></span>
                        </li>
                        <li class="list-group-item">PHP</li>
                        <li class="list-group-item">Object Oriented Programming</li>
                        <li class="list-group-item">REST API</li>
                        <li class="list-group-item">Windows and Linux Apache</li>
                    </ul>
                </div>
                <div class="custom-skills">
                    <ul class="list-group">
                        <li class="list-group-item active">
                            Frontend
                            <span class="badge badge-primary badge-pill"><i class="fa fa-laptop"></i></span>
                        </li>
                        <li class="list-group-item">JavaScript and jQuery</li>
                        <li class="list-group-item">Bootstrap and Fontawesome</li>
                        <li class="list-group-item">HTML and CSS</li>
                    </ul>
                </div>
                <div class="custom-skills">
                    <ul class="list-group">
                        <li class="list-group-item active">
                            Database
                            <span class="badge badge-primary badge-pill"><i class="fa fa-database"></i></span>
                        </li>
                        <li class="list-group-item">MySQL</li>
                        <li class="list-group-item">MongoDB</li>
                        <li class="list-group-item">PostgreSQL</li>
                    </ul>
                </div>
                <div class="custom-skills">
                    <ul class="list-group">
                        <li class="list-group-item active">
                            Source Control 
                            <span class="badge badge-primary badge-pill"><i class="fa fa-code-fork"></i></span>
                        </li>
                        <li class="list-group-item">SCRUM and Agile</li>
                        <li class="list-group-item">Jira</li>
                        <li class="list-group-item">Git and Github</li>
                    </ul>
                </div>
        </div>
    </div>
</template>

<script>

export default {
    name: 'About',
    props: {
        msg: String
    }
}
</script>
