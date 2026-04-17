# Short Response — LG 7.0: Responsive Units

Answer each question in 2–3 sentences. 

---

## Question 1 — Describe

What is the difference between a static unit like `px` and a responsive unit like `%` or `vh`?

Describe what makes a unit responsive and why that matters when building a website.

The difference between a static unit like `px` verses a responsive unit like `%` or `vh` is how `px` doesnt change in size at all regardless of whether the screen you're viewing it through is smaller or bigger. This matters when building a website cause it can result in a website breaking or just being really hard to view through a different device. With `%` or `vh`, it allows the units to adjust based off the device, allowing itself to shrink or grow to meet the size of the device's window.

---

## Question 2 — Explain

Look at these two CSS rules:

```css
.image {
  width: 400px;
}

.image {
  width: 50%;
}
```

Explain what happens to the image on a small screen with each rule. Why does one behave better than the other?

When the first CSS rule is put on a small screen, it will seem huge and might a viewer might not even be able to see the entire thing because it doesn't adjust based off your window. Meanwhile when the second CSS rule is put on a small screen it will only take up 50 percent of the screen because the unit used allows the image to adjust based off the view of the device instead of likely exceeding it like how the previous CSS rule would.




