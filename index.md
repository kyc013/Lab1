Create a new file called index.md. This is where you'll create your User Page, which should include content that introduces who you are as a programmer and as a person. Your User Page must be made with Markdown. For this assignment, your page must include the following:

    Pictures
    All the core Markdown constructs in GitHub Flavored Markdown 

    Links to an external site.
        Headings o
        Styling text o
        Quoting text o
        Quoting code o
        External Links o
        Section links o
        Relative links (Link to another .md file or an image in your repo. If linking to an image, encode it as a regular link rather than an image.) o
        Ordered and Unordered Lists o
        Task lists o

Once you are finished, publish your web page through Github Pages - instructions here
Links to an external site.. Include the URL to the published site in your README.md file.

# Lab 1  
**Kyungwoo Choi**  

Hello.
I don't see myself much as a *programmer* so I'll just talk about what I like.

I like movies, some of my favorite being the following:

- A Streetcar Named Desire
- Roman Holiday
- Edward Scissorhands
- Rocco and His Brothers
- The Man From Nowhere

I also like novels. Out of the ones I've read so far, here's my list of favorite books:

1. The Great Gatsby
2. The Catcher In The Rye
3. The Little Prince
4. Frankenstein
5. To Kill A Mockingbird

I used to listen to a lot of Elvis songs and interviews in highschool. One of my favorite quotes of his goes like this:

[![Cn3De3gUkAAupR9](https://github.com/kyc013/Lab1/assets/147003854/cf5aee86-c504-4024-ba70-729bf24e6791)](https://github.com/kyc013/Lab1/blob/main/Cn3De3gUkAAupR9.jpg)

```
You only pass through this life once, you don't come back for an encore.
```

Here's a list of my bucket list.
- [ ] Skydiving
- [x] Watching a black and white movie in a theater
- [x] Staying awake for more than 24 hours
- [ ] Staying a week in Paris
- [ ] Seeing a meteor shower

Lastly, a quiz:
Guess what the following code would output.

    import turtle 
     
    # Set up the turtle 
    turtle.setup(400, 500) 
    wn = turtle.Screen() 
    wn.title("How to draw a face using turtle") 
    wn.bgcolor("lightgreen") 
     
    # Create a turtle to draw the face 
    t = turtle.Turtle() 
    t.color("blue") 
    t.pensize(5) 
     
    # Draw the head 
    t.penup() 
    t.goto(-100, 100) 
    t.pendown() 
    t.circle(50) 
     
    # Draw the eyes 
    t.penup() 
    t.goto(-70, 70) 
    t.pendown() 
    t.circle(10) 
     
    t.penup() 
    t.goto(-30, 70) 
    t.pendown() 
    t.circle(10) 
     
    # Draw the nose 
    t.penup() 
    t.goto(-50, 50) 
    t.pendown() 
    t.goto(-50, 30) 
    t.goto(-60, 40) 
    t.goto(-40, 40) 
    t.goto(-50, 30) 
     
    # Draw the mouth 
    t.penup() 
    t.goto(-60, 10) 
    t.pendown() 
    t.goto(-40, 10) 
     
    # Hide the turtle 
    t.hideturtle() 
     
    # Keep the window open until it is closed 
    wn.mainloop() 

I got a lot of help from the [Basic Syntax](https://www.markdownguide.org/basic-syntax/) to create this page.

[jump to top page](# Lab 1)
