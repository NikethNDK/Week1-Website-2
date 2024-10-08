Clone of LinkedIn
<<<<<<< HEAD
The navbar is configured as a flexbox and furhter the navbar icons are arranged as flexbox with flex direction set as row.
The highlighting of the text is done by changing the color image is done by controlling the opacity when hovered. Another class is used to remoe the hover filter effect on the user image in the navbar
=======

Navbar is set with a fixed position so that it will always remain at the top. it is also provided with display property as flex so that search and icons are all in the same axis
The search part is combined of an image and a input field.
The icons in the navbar are again put in another flex. 
The hover effect on the icons are done by adding a filter to alter the brignetess
To avoid the hover effect on the images the filter effect is removed with another class.

Body part
The main body container is divided in to three grid columns left main and right.

Left sidebar
it is further divided into 4 smaller cards. 
    The first card is the profile card.
    The second one left-card2,left-card3 and left-card4. left-card2 is kept as the base and the height of the rest is adjusted based on the requirement.
    Class used to keep the work details is reused for aligning the items in the 2 class also.
    Hover effect is applied to make the underline and color change

Main content
    Main content is mainly divided into two parts one for drafting the post and other as the item to be posted by the user

    write a post -- class
        it contains the first section in the main content - ie the profile image, input and the actions available to post. 
        Work details class which is defined for the left section is used for aligning media, contribute expertise and write article
    
    horizontail line decorator used line-with-text
        This sets a border to 0 and then sets border top pixels. It also uses the flexgrow property to fill up the rest of the area.
    
    post-card
        The entire details of the post is kept inside this card. The main classes under this section are:
            a. post-user-details
                it contains the user image and the user details
            b. content-description
                it contains the brief about the content and the post(i.e image)
            c. reactions
                it contains which all reactions the users has given for the post and the number of comments in the left side
            d. line1
                a decorator used to separate the elements
            e. reaction-button
                reactions such as like celebration and so on place equaly.Also animation is applied explicilty to the like class for hover effect and popup of available reaction emojis.

    Note: Copy of the same card is made to populate the content.

Right sidebar
    The entire section is divided in to two parts
    1. news-module
        a. right section-it contains the linkedin logo and the ;i; button
        b. subheadings-all the rest of the section are repicated using the same class.  Inorder to keep the footer earlier class 'work-detail' is reused
        c. show more is wrapped inside a button tag along with the frop down arrow svg
        d. puzzles- all puzzles are wrapped into diffetent containers and given a hover effect
    
    2.premium-ad-card
        a. reuses the class 'work-detail' to place the first element and modified the same class with flex property justify content:end 
        b. img-logo - this class is used to align the images
        c.tagline class is to align the text
        d. A button tag is used to create it
        e. position is kept fixed when this card reaches by using css sticky property
    
    3. try-linkedin-card- it is the container to hold the items. The items are addded as span and p tag. CSS is applied by modifying the work-detail class to this child and adding custom css to the elements.
    position is kept fixed when this card reaches by using css sticky property


    4. linkedin details
    the actions are added using a tag.then the container is kept sticky

    5. linkedin footer
    logo and text is placed side by side using span and it is fixed at a position using sticky





    
        



>>>>>>> a48213c859d9f89e23f49628119b073f9e1185fe
