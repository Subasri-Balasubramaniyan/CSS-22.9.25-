1. 🎞️ Animations in CSS

CSS animations let you create motion effects and transitions between styles.

Key Points:

Use @keyframes to define animation steps.

Apply animation with properties like animation-name, animation-duration, animation-iteration-count.

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.box {
  animation-name: fadeIn;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}


✅ Other useful properties:

animation-delay → start delay

animation-timing-function → speed curve (ease, linear, etc.)

animation-direction → normal, reverse, alternate

2. 📏 CSS Units

CSS units define the measurement of values like font-size, margin, padding.

Types of Units

Absolute Units → Fixed values

px (pixels), cm, mm, in, pt, pc

p { font-size: 16px; }


Relative Units → Depend on other elements

% → relative to parent size

em → relative to parent font-size

rem → relative to root (html) font-size

vw / vh → relative to viewport width/height

p { font-size: 1.5em; }  /* 1.5 × parent font-size */

3. 🎨 Types of CSS
A. By Inclusion

Inline CSS → inside element (style attribute)

Internal CSS → inside <style> tag in <head>

External CSS → separate .css file linked with <link>

B. By Selectors

Element selector → p { }

Class selector → .classname { }

ID selector → #idname { }

Group selector → h1, h2 { }

Attribute selector → input[type="text"] { }

Pseudo-class → a:hover { }

Pseudo-element → p::first-letter { }

4. 📐 px vs em
Unit	Meaning	Based On	Example
px	Pixels (absolute)	Fixed size	font-size: 16px; → always 16px
em	Relative unit	Parent’s font-size	If parent = 20px, 1.5em = 30px

🔑 Tip:

Use px for borders, icons, fixed layouts.

Use em/rem for font-size and scalable designs.

5. 🌈 Colors in CSS

CSS supports multiple ways to set colors.

Types of Color Values

Named Colors → red, blue, green

Hexadecimal → #ff0000 (red), #0f0 (green)

RGB → rgb(255, 0, 0)

RGBA (with transparency) → rgba(255, 0, 0, 0.5)

HSL → hsl(0, 100%, 50%)

HSLA → hsla(200, 100%, 50%, 0.3)

Gradients →

background: linear-gradient(to right, red, yellow);
