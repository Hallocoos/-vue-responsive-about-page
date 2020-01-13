<template>
    <div class="about-card">
        <div class="card-title">
            <img height="50px" src="https://i.pinimg.com/originals/d3/69/d9/d369d9056795f553e244da66e8297cca.png" alt="avatar" class="avatar">
            <div class="title-text-content">
                <p>About Me</p>
                <h2>Jonathan Doe</h2>
            </div>
        </div>
        <div class="card-content">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta nihil sit deleniti cum eveniet dolores, voluptatibus nostrum distinctio numquam earum tempora reiciendis ab odio impedit quibusdam id ducimus repudiandae veniam esse explicabo culpa. Numquam amet dolores enim ipsa! Quas laudantium enim placeat incidunt commodi soluta hic itaque quo optio illum.</p>
        </div>
        <table width="100%">
            <tr>
                <th>Requirement</th>
                <th>Solution</th>
            </tr>
            <tr>
                <td>Design</td>
                <td>PhotoShop, Figma, Canva, Adobe XD</td> 
            </tr>
            <tr>
                <td>Front-end</td>
                <td>React.js, Vue.js, Nuxt.js, HTML, CSS, JavaScript</td> 
            </tr>
            <tr>
                <td>Back-end</td>
                <td>Node.js, Express.js, Mongo, GraphQL</td> 
            </tr>
            <tr>
                <td>ML</td>
                <td>ML5, TensorFlow, Algorithm Design</td> 
            </tr>
            <tr>
                <td>Shop</td>
                <td>Stripe, PayFast, E-commerce, CMS</td> 
            </tr>
        </table>

        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laboriosam dolor at quae error eveniet nostrum ratione, maxime, officia repudiandae explicabo non dignissimos deleniti sed laborum! Quam molestias, nemo enim vitae, minus doloribus exercitationem repudiandae harum magnam eius eum ducimus illo adipisci. Veniam minus doloribus voluptas voluptatem consequuntur iusto sint dolore.</p>
        
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestiae quo doloribus voluptatem, nihil in optio odit unde doloremque laboriosam dolores officiis? Cum ratione modi minima nulla veritatis eius ab blanditiis nobis cumque? Tempore eius dolorem similique voluptatem excepturi veniam enim, atque reprehenderit nobis dolor pariatur ipsam assumenda aut ipsa modi.</p>
    </div>
</template>

<style lang="sass" scoped>
    .about-card
        background: #333
        padding: 3em
        border-radius: 10px
        color: white
        .card-title
            display: flex
            align-items: center
            background: #222
            border-radius: 10px
            .avatar
                border: 1px solid rgba(255, 255, 255, 0.4)
                border-radius: 50%
                margin: 0 30px
        .title-text-content
            p
                margin-bottom: 0
                color: rgb(210, 210, 210)
            h2
                margin-top: 0

    .card-content p
        line-height: 1.5
        margin: 30px auto

    table
        border-spacing: 0px
        margin: 50px auto
        tr th, tr td 
            border: 1px solid white
            border-top: none
            padding: 10px
            text-align: center
            &:first-of-type
                border-left: none
            &:nth-of-type(2)
                border-right: none
</style>