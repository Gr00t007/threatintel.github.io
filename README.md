doctype html
html(lang='en')

    head

        meta(charset='utf-8')
        meta(name='viewport', content='width=device-width, initial-scale=1, shrink-to-fit=no')
        meta(name='description', content='')
        meta(name='author', content='')

        title Threat Intel

        link(rel='icon', type='image/x-icon', href='assets/img/favicon.ico')

        // Font Awesome icons (free version)
        script(src='https://use.fontawesome.com/releases/v5.15.4/js/all.js', crossorigin='anonymous')

        // Google fonts
        link(href='https://fonts.googleapis.com/css?family=Saira+Extra+Condensed:500,700', rel='stylesheet', type='text/css')
        link(href='https://fonts.googleapis.com/css?family=Muli:400,400i,800,800i', rel='stylesheet', type='text/css')

        // Core theme CSS (includes Bootstrap)
        link(href='css/styles.css', rel='stylesheet')

    body#page-top

        // Navigation
        nav#sideNav.navbar.navbar-expand-lg.navbar-dark.bg-primary.fixed-top
            a.navbar-brand.js-scroll-trigger(href='#page-top')
                span.d-block.d-lg-none Clarence Taylor
                span.d-none.d-lg-block
                    img.img-fluid.img-profile.rounded-circle.mx-auto.mb-2(src='assets/img/profile.jpg', alt='...')
            button.navbar-toggler(type='button', data-bs-toggle='collapse', data-bs-target='#navbarResponsive', aria-controls='navbarResponsive', aria-expanded='false', aria-label='Toggle navigation')
                span.navbar-toggler-icon
            #navbarResponsive.collapse.navbar-collapse
                ul.navbar-nav
                    li.nav-item
                        a.nav-link.js-scroll-trigger(href='#about') About
                    li.nav-item
                        a.nav-link.js-scroll-trigger(href='#experience') Experience
                    li.nav-item
                        a.nav-link.js-scroll-trigger(href='#education') Education
                    li.nav-item
                        a.nav-link.js-scroll-trigger(href='#skills') Skills
                    li.nav-item
                        a.nav-link.js-scroll-trigger(href='#interests') Interests
                    li.nav-item
                        a.nav-link.js-scroll-trigger(href='#awards') Awards

        // Page Content
        .container-fluid.p-0

            // About
            section#about.resume-section
                .resume-section-content
                    h1.mb-0
                        | Clarence 
                        span.text-primary Taylor
                    .subheading.mb-5
                        | 3542 Berry Street · Cheyenne Wells, CO 80810 · (317) 585-8468 · 
                        a(href='mailto:name@email.com') name@email.com
                    p.lead.mb-5
                        | I am experienced in leveraging agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition.
                    .social-icons
                        a.social-icon(href='#!')
                            i.fab.fa-linkedin-in
                        a.social-icon(href='#!')
                            i.fab.fa-github
                        a.social-icon(href='#!')
                            i.fab.fa-twitter
                        a.social-icon(href='#!')
                            i.fab.fa-facebook-f

            hr.m-0

            // Experience
            section#experience.resume-section
               .resume-section-content
                    h2.mb-5 Experience

                    .d-flex.flex-column.flex-md-row.justify-content-between.mb-5
                        .flex-grow-1
                            h3.mb-0 Senior Web Developer
                            .subheading.mb-3 Intelitec Solutions
                            p
                                | Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
                        .flex-shrink-0
                            span.text-primary March 2013 - Present

                    .d-flex.flex-column.flex-md-row.justify-content-between.mb-5
                        .flex-grow-1
                            h3.mb-0 Web Developer
                            .subheading.mb-3 Intelitec Solutions
                            p
                                | Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.
                        .flex-shrink-0
                            span.text-primary December 2011 - March 2013

                    .d-flex.flex-column.flex-md-row.justify-content-between.mb-5
                        .flex-grow-1
                            h3.mb-0 Junior Web Designer
                            .subheading.mb-3 Shout! Media Productions
                            p
                                | Podcasting operational change management inside of workflows to establish a framework. Taking seamless key performance indicators offline to maximise the long tail. Keeping your eye on the ball while performing a deep dive on the start-up mentality to derive convergence on cross-platform integration.
                        .flex-shrink-0
                            span.text-primary July 2010 - December 2011

                    .d-flex.flex-column.flex-md-row.justify-content-between
                        .flex-grow-1
                            h3.mb-0 Web Design Intern
                            .subheading.mb-3 Shout! Media Productions
                            p
                                | Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.
                        .flex-shrink-0
                            span.text-primary September 2008 - June 2010

            hr.m-0

            // Education
            section#education.resume-section
                .resume-section-content
                    h2.mb-5 Education

                    .d-flex.flex-column.flex-md-row.justify-content-between.mb-5
                        .flex-grow-1
                            h3.mb-0 University of Colorado Boulder
                            .subheading.mb-3 Bachelor of Science
                            div Computer Science - Web Development Track
                            p GPA: 3.23
                        .flex-shrink-0
                            span.text-primary August 2006 - May 2010

                    .d-flex.flex-column.flex-md-row.justify-content-between
                        .flex-grow-1
                            h3.mb-0 James Buchanan High School
                            .subheading.mb-3 Technology Magnet Program
                            p GPA: 3.56
                        .flex-shrink-0
                            span.text-primary August 2002 - May 2006

            hr.m-0

            // Skills
            section#skills.resume-section
                .resume-section-content
                    h2.mb-5 Skills
                    .subheading.mb-3 Programming Languages & Tools
                    ul.list-inline.dev-icons
                        li.list-inline-item
                            i.fab.fa-html5
                        li.list-inline-item
                            i.fab.fa-css3-alt
                        li.list-inline-item
                            i.fab.fa-js-square
                        li.list-inline-item
                            i.fab.fa-angular
                        li.list-inline-item
                            i.fab.fa-react
                        li.list-inline-item
                            i.fab.fa-node-js
                        li.list-inline-item
                            i.fab.fa-sass
                        li.list-inline-item
                            i.fab.fa-less
                        li.list-inline-item
                            i.fab.fa-wordpress
                        li.list-inline-item
                            i.fab.fa-gulp
                        li.list-inline-item
                            i.fab.fa-grunt
                        li.list-inline-item
                            i.fab.fa-npm
                    .subheading.mb-3 Workflow
                    ul.fa-ul.mb-0
                        li
                            span.fa-li
                                i.fas.fa-check
                            | Mobile-First, Responsive Design
                        li
                            span.fa-li
                                i.fas.fa-check
                            | Cross Browser Testing & Debugging
                        li
                            span.fa-li
                                i.fas.fa-check
                            | Cross Functional Teams
                        li
                            span.fa-li
                                i.fas.fa-check
                            | Agile Development & Scrum

            hr.m-0

            // Interests
            section#interests.resume-section
                .resume-section-content
                    h2.mb-5 Interests
                    p
                        | Apart from being a web developer, I enjoy most of my time being outdoors. In the winter, I am an avid skier and novice ice climber. During the warmer months here in Colorado, I enjoy mountain biking, free climbing, and kayaking.
                    p.mb-0
                        | When forced indoors, I follow a number of sci-fi and fantasy genre movies and television shows, I am an aspiring chef, and I spend a large amount of my free time exploring the latest technology advancements in the front-end web development world.

            hr.m-0

            // Awards
            section#awards.resume-section
                .resume-section-content
                    h2.mb-5 Awards & Certifications
                    ul.fa-ul.mb-0
                        li
                            span.fa-li
                                i.fas.fa-trophy.text-warning
                            | Google Analytics Certified Developer
                        li
                            span.fa-li
                                i.fas.fa-trophy.text-warning
                            | Mobile Web Specialist - Google Certification
                        li
                            span.fa-li
                                i.fas.fa-trophy.text-warning
                            | 1
                            sup st 
                            | Place - University of Colorado Boulder - Emerging Tech Competition 2009
                        li
                            span.fa-li
                                i.fas.fa-trophy.text-warning
                            | 1
                            sup st 
                            | Place - University of Colorado Boulder - Adobe Creative Jam 2008 (UI Design Category)
                        li
                            span.fa-li
                                i.fas.fa-trophy.text-warning
                            | 2
                            sup nd 
                            | Place - University of Colorado Boulder - Emerging Tech Competition 2008
                        li
                            span.fa-li
                                i.fas.fa-trophy.text-warning
                            | 1
                            sup st 
                            | Place - James Buchanan High School - Hackathon 2006
                        li
                            span.fa-li
                                i.fas.fa-trophy.text-warning
                            | 3
                            sup rd 
                            | Place - James Buchanan High School - Hackathon 2005

        // Bootstrap core JS
        script(src='https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js')

        // Core theme JS
        script(src='js/scripts.js')
