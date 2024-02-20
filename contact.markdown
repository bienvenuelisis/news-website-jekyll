---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Nous contacter
description: A partir votre blog, obtenez une application mobile moderne, améliorez votre engagement et augmentez vos revenus.
---


<!-- Header -->
<header id="header" class="header bg-dark-blue">
    {% include news-app.html %}
</header> <!-- end of ex-header -->
<!-- end of header -->


<!-- Form -->
<div class="ex-form-1 pt-6 pb-5">
    <div class="container">
        <div class="row">
            <div class="col-xl-10 offset-xl-1">
                <h1 style="margin: auto;">Contactez nous</h1>
            </div> <!-- end of col -->
        </div> <!-- end of row -->
    </div> <!-- end of container -->
    <br><br>
    <div class="container">
        <div class="row">
            <div class="col-xl-10 offset-xl-1">
                <!-- Contact Form -->
                <form method="POST" action="https://formspree.io/xknqezbp" id="contactForm" class="mb-6"
                      data-toggle="validator"
                      data-focus="false">
                    <div class="form-group">
                        <input type="text" class="form-control-input" id="name" required>
                        <label class="label-control" for="name">Name</label>
                        <div class="help-block with-errors"></div>
                    </div>
                    <div class="form-group">
                        <input type="email" class="form-control-input" id="email" required>
                        <label class="label-control" for="email">Email</label>
                        <div class="help-block with-errors"></div>
                    </div>
                    <div class="form-group">
                        <textarea class="form-control-textarea" id="message" required></textarea>
                        <label class="label-control" for="message">Message</label>
                        <div class="help-block with-errors"></div>
                    </div>
                    <div class="form-group">
                        <button type="submit" class="form-control-submit-button">Envoyer</button>
                    </div>
                    <div class="form-message">
                        <p id="my-form-status"></p>
                    </div>
                </form>
                <!-- end of contact form -->
            </div> <!-- end of col -->
        </div> <!-- end of row -->
    </div> <!-- end of container -->
</div> <!-- end of ex-form-1 -->
<!-- end of form -->