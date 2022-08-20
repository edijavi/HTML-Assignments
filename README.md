## HTML Assignments
1. Read more about HTML and try to answer as many questions as you can from the
HTML - Terminology & Definitions file, which you can find attached in the email.
2. Assignment(Lists):
    a. An unordered shopping list of your favorite foods
    b. An ordered list of todo’s you need to get done today
    c. An unordered list inside of an ordered list, of places you’d like to visit someday
    d. An ordered list inside of an unordered list, of your all time top 5 favorite video
    games or movies
3. Assignment(Links & Images):
    1. Create a new directory named links-and-images
    2. Within that directory, create a new file named index.html
    3. Fill in the usual HTML boilerplate
    4. Set the title to “Links & Images”
    5. Finally, add the following h1 to the body: <h1>Homepage</h1>
    6. Create another HTML file named about.html
    7. Back in the index page, add the following anchor element below the <h1>
    element: <a href=”https://theuselessweb.com/”>click me</a>
    <a href="about.html">About</a>
    8. Open the index file in a browser and click on the About link to make sure it is all
    wired together correctly. Clicking the link should go to the empty about page you
    just created (you can fill it in if you like)
    9. Create a directory named pages within the links-and-images directory and move
    the about.html file into this new directory. Refresh the index page in the browser
    and then click on the about link. It will now be broken. This is because the
    location of the About page file has changed. To fix this, you just need to update
    the about link href value to include the pages directory since that is the new
    location of the about file relative to the index file. <a
    href="./pages/about.html">About</a>
    10. In many cases, this will work just fine; however, you can still run into unexpected
    issues with this approach. Prepending ./ before the link will in most cases
    prevent such issues. By adding ./ you are specifying to your code that it should
    start looking for the file/directory relative to the current directory. You can also
    add a link to get back from the About page to your homepage
    k. To use images on your own websites, you can use a relative path:
    11. Create a new directory named images within the links-and-images
    project
        +. Next, download any image .jpg/.png and move it into the images
        directory you just created
        iii. Rename the image to first-img.jpg/.png
        +. Add the image to the index.html file:
        <img src="images/first-img.jpg">
        +. Save the index.html file and open it in a browser to view your image in all
        its glory. Remember to use ./ before the images/first-img.jpg if your
        image isn’t loading
        +. As a bit of practice, add an alt attribute to the first-img you added to the
        links-and-images project.
4. Assignment(Main HTML project): For presentation make a few page presentation
website about your hobby/favorite books/movies etc. Your website should contain a
homepage with a link to go inside to the page where your material should be presented
in list form, with links leading to pages with the description(text & image) of your chosen
subject. As an added bonus, you can make each list element into a link, leading to the
page where additional information about said subject can be found(images are always
welcomed, just don't over do it :D)