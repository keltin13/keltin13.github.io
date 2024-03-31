---
layout: post
title:  "Ode to Transformer"
date:   2021-03-07 15:56:18 -0500
ad_image_path: /assets/post_assets/2021-03-07-ode-to-transformer/poem_square.png
ad_title: ode to transformer
ad_description: A poem-writing AI.
---

The transformer-based neural networks have become the state of the art in Natural Language Processing, most notably in
text generation. They can create paragraphs that would easily fool you into thinking they were written by humans. But how well
could they grasp the concept of poetry?

To find out, I took one of the leading text-generation models at the time, called GPT-2, created by OpenAI, and fine-tuned it on
a large collection of English-language poetry. It did not take much fiddling to produce some really interesting results. I trained
the model in such a way that all you had to do was provide the model with a title, and it would generate the body of the poem. Here
are some of the results.

<div class="poem_title" style="margin-left: 40px">
    A Rainy Afternoon
</div>
<div class="poem_body" style="margin-left: 40px">
    I have a dream, a vision of the past; <br/>
    A cloudless sky and an ocean's calm, <br/>
    I am alone in my room with the stars, <br/>
    And they are all asleep on their way to heaven. <br/>
    The moon is shining through the window pane; <br/>
    She has gone down into her silver bed: <br/>
    Her face looks like a mirror that was made for me!
</div>

<div class="poem_title" style="margin-left: 40px">
    Dusk
</div>
<div class="poem_body" style="margin-left: 40px">
    She sits alone, so full and calm, <br/>
    Yet looks to every hour of night, <br/>
    And turns her lips in silent vow, <br/>
    She dreams on a far-off sea <br/>
    That is deep and sad and still.
</div>

I hosted my trained model on the Google Cloud AI Training and Prediction Service, and created a web interface with ReactJS to request
poems from the model.
