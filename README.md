# Some Readme Math
<p>Using LaTeX in README.md examples</p>

## Integral Test with Leibniz rule:

$$ F(x) = \int_{cos(x)}^{ln(x)} sec(x) dx$$
$$ F'(x) = \frac{d}{dx} \int_{cos(x)}^{ln(x)} sec(x) dx $$

### Chain rule for $F(ln(x))$:

$$ \frac{d}{dx}F(ln(x)) = \frac{F'(ln(x))}{x} $$

### Chain rule for $F(cos(x))$:

$$ \frac{d}{dx}F(cos(x)) = -sin(x)F'(cos(x)) $$

## Substitute the derivatives for $F(ln(x))$ and $F(cos(x))$ to get the result of the integral

$$ \frac{d}{dx} \int_{cos(x)}^{ln(x)} sec(x) dx = \frac{sec(ln(x))}{x} - [-sin(x)sec(cos(x))]$$
$$ \frac{d}{dx} \int_{cos(x)}^{ln(x)} sec(x) dx = \frac{sec(ln(x))}{x} + sin(x)sec(cos(x))$$
