"You come highly recommended. I'm really looking forward to working with you on this."

You've been hired as a consultant to develop an online image manipulation program by Prismatic Software, LLC, and it's your first week. After talking with the client, G. Hopper, you've both decided the best place to start is a color picker.

"We need the color picker for a few possible scenarios. We want to use it on other web pages like tutorials so we can help new graphic designers learn about color. We'll be using it this way first to help grow our audience. Later on, we'll want to use it in our online app so they can use the same tool that they're already familiar with."

You ask Hopper to describe the color picker more.

"Sure. Have you seen color pickers in software like Adobe Photoshop (Links to an external site.) or even Google (Links to an external site.)? Well, we want something like that eventually. One key difference is we want to use RGB and Barycentric Maxwell hues, so instead of that square, we'll be using a triangle and a luminance slider."

Barycentric Maxwell hues?

"That's right. They're similar to hue-saturation-value (Links to an external site.) but make it really easy to quickly and easily apply filters and change images. Instead of red, green, and blue, they use ρ (rho) for red, ɣ (gamma) for green, (β) beta for blue, and L for luminance. Barycentric means that all the values are between 0.0 and 1.0 and that ρ, ɣ, and β all sum to 1.0. A value of 0.0 means that there is none of the channel—no red, for example—and a value of 1.0 means only that channel—a pure green would have a ɣ of 1.0. Luminance ranges from no brightness at 0.0 to maximum brightness at 1.0. That means that white is about (0.3, 0.3, 0.3, 1.0) and yellow is (0.5, 0.5, 0, 1.0) in (ρ, ɣ, β, L) order.

"It might sound a bit confusing, but take a look at this paper. Look at sections 3 and 4."

Hopper hands you a document  Download a document.

"If you hold a pen over the Maxwell hues triangle on page 2 and start at pure blue in the bottom-left corner, then as you move your pen to the right you're using less blue and adding more red. That is, β decreases and ρ increases, but you still have a single color. That's why everything adds up to 1.0."

You ask about priorities.

"Well, the most important thing is users being able to enter and convert RGB to ρɣβL. They also need a way to visualize the color, so just a square with the current color would be great for now. Eventually, we'll want them to enter ρɣβL values and have them converted back to RGB. It'd be best if the RGB values were also between 0.0 and 1.0 since most of our potential customers are familiar with that. Most aren't very technical, though, so we won't need to add hexadecimal support until later."

Since you're a contractor, you ask about payment.

"Contractors are paid hourly. You'll be using Pivotal Tracker to plan the project, right? You can just write how long you spend on each story in each comment field. I've worked with agile developers before, so I understand about points and estimates. Just make your best guess for points. Don't forget the actual time you spend, though, if you want to get paid! But remember, we only have enough to pay you for six hours, so don't spend longer than that right now. Our tech lead will need each of those stories linked to your Git commits, too, for when they do the code review."

Hopper checks the time.

"Let me know if you have any questions. I'm looking forward to seeing what you put together!"
