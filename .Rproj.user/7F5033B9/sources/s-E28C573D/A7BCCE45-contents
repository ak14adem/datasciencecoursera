shape_names <- c(
"circle", paste("circle", c("open", "filled", "cross", "plus", "small")), "bullet",
"square", paste("square", c("open", "filled", "cross", "plus", "triangle")),
"diamond", paste("diamond", c("open", "filled", "plus")),
"triangle", paste("triangle", c("open", "filled", "square")),
paste("triangle down", c("open", "filled")),
"plus", "cross", "asterisk"
)
shapes <- data.frame(
shape_names = shape_names,
x = c(1:7, 1:6, 1:3, 5, 1:3, 6, 2:3, 1:3),
y = -rep(1:6, c(7, 6, 4, 4, 2, 3))
)
ggplot(shapes, aes(x, y)) +
geom_point(aes(shape = shape_names), fill = "red", size = 5) +
geom_text(aes(label = shape_names), nudge_y = -0.3, size = 3.5) +
scale_shape_identity() +
theme_void()
example <- matrix(c(1,2,3,4,5,6,7,8), nrow = 4, ncol = 2)
