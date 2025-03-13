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


## U-substitution

$$ \int \frac{e^{\sqrt{4y+8}}}{\sqrt{4y+8}} dy $$
$$ u = 4y+8 → \frac{du}{dy} = 4 → dy = \frac{du}{4} → \frac{1}{4}\int \frac{e^{\sqrt{u}}}{\sqrt{u}} du$$
$$ v = \sqrt{u} → \frac{dv}{du} = \frac{1}{2\sqrt{u}} → du = 2\sqrt{u}dv $$
$$ \frac{1}{2}\int e^{v} dv = \frac{e^v}{2} = \frac{e^{\sqrt{u}}}{2} = \frac{e^{\sqrt{4y+8}}}{2} + C $$
