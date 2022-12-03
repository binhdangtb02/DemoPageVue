<template>
    <section class="contact" id="contact">
        <div class="contact-header">
            <h2>CONTACT</h2>
            <hr />
        </div>
        <div class="contact-info">
            <div>
                <h2>address</h2>
                <p>123 Street, New York (USA)</p>
            </div>
            <div>
                <h2>PHONE</h2>
                <p>+123 456 789
                </p>
            </div>
            <div>
                <h2>email</h2>
                <p>info@myemail.com</p>
            </div>
        </div>
        <div class="contact-form">
            <form action="">
                <div class="general-info">
                    <div>
                        <input type="text" name="name" placeholder="Name *">
                        <hr class="hr-form">
                    </div>
                    <div>
                        <input type="text" name="email" placeholder="Email *">
                        <hr class="hr-form" />
                    </div>
                </div>
    
                <input class="message-info" type="text" name="message" placeholder="Message">
                <hr class="hr-form" />
    
            </form>
            <input type="submit" value="send" class="submit-btn">
        </div>
    </section>
</template>