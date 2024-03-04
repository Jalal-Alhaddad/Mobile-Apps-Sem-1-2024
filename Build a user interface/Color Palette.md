# Color Palette

- [Color Palette](#color-palette)
  - [Color Palette components](#color-palette-components)
    - [Brand Color](#brand-color)
    - [Supporting Colors](#supporting-colors)
    - [Neutrals](#neutrals)
    - [Accent Colors](#accent-colors)
    - [Tints and Shades](#tints-and-shades)
  - [Choosing the Right Palette](#choosing-the-right-palette)
  - [Color Tokens: Defining Colors in Design Systems](#color-tokens-defining-colors-in-design-systems)
    - [Categories of color tokens](#categories-of-color-tokens)
      - [Primitive Tokens](#primitive-tokens)
      - [Semantic Tokens](#semantic-tokens)
      - [Component-Specific Tokens](#component-specific-tokens)
    - [Color Naming Conventions](#color-naming-conventions)
  - [Using Color Palette Effectively](#using-color-palette-effectively)
    - [Other Guidelines](#other-guidelines)

> A color palette is a carefully selected set of colors used in a design project, providing the necessary colors to create a cohesive visual identity and evoke specific emotions in the user

## Color Palette components

### Brand Color

- The Heart of the Palette: This is the core color that represents the brand and is used consistently across all design elements.
- Careful Consideration: Choosing the brand color is crucial as it becomes strongly associated with the brand in the minds of users.
- Example: Think of the iconic red of Coca-Cola or the vibrant blue of Twitter.

### Supporting Colors

- Adding Depth and Harmony: These colors complement the brand color, adding visual interest and depth to the design.
- Strategic Use: They should work harmoniously with the brand color and be used strategically to:
  - Highlight specific elements or sections: Call to action buttons or key information might use a supporting color.
  - Create contrast and hierarchy: A supporting color can create visual separation between elements.
- Example: The blue and yellow alongside the red brand color of McDonald's exemplifies supporting colors effectively.

### Neutrals

- Providing Balance and Versatility: These colors lack strong hues, typically including white, black, gray, and beige.
- Multi-Purpose Workhorses: They are often used for:
  - Backgrounds: Neutral colors provide a clean canvas for other elements to stand out.
  - Text: Ensuring readability and accessibility is crucial, often achieved with neutral text colors.
  - Subtle Accents: A touch of a neutral color can add subtle visual interest.
- Balancing Act: Neutrals create a sense of balance and can be used to make other, more vibrant colors stand out.

### Accent Colors

These are bold colors used sparingly to add a pop of vibrancy or draw attention to specific elements (in some palette).

### Tints and Shades

These are variations of a base color created by adding white (tints) or black (shades) to adjust their lightness or darkness (in some palette).

## Choosing the Right Palette

- Brand Identity: The colors should reflect the brand's personality and values. Think of a playful brand using bright, energetic colors, while a sophisticated brand might choose more subdued tones.
- Target Audience: Consider the preferences and cultural associations of your target audience. Different cultures may have different color associations.
- Accessibility: Ensure your color choices meet accessibility guidelines for people with visual impairments. This ensures everyone can easily perceive and understand the information presented.
- Color Harmony: Colors should work well together and create a cohesive visual experience. You can utilize various color theory tools and principles to achieve this.

## Color Tokens: Defining Colors in Design Systems

> A color token is a reusable variable that stores a specific color value within a design system. It acts like a named placeholder for a color, allowing designers and developers to consistently use the same color across various design elements

- Consistency: Ensures all instances of a color appear identical throughout the design system.
- Maintainability: Makes it easier to update color values by changing the token definition instead of modifying each instance individually.
- Scalability: Enables easy adaptation of the color palette across different contexts and platforms.

### Categories of color tokens

#### Primitive Tokens

- Represent the base color values themselves: These are the raw color codes, often expressed in hexadecimal (e.g., `#FF0000`) or other color formats (e.g., `rgb(255, 0, 0)`)
- Examples:
  `@ red-IOO (might represent pure red)`
  `@ red-200 (might represent a lighter shade of red)`
  `@ red-300 (might represent a darker shade of red)`
- Alternative names: Base tokens, global tokens, atomic tokens

#### Semantic Tokens

- Describe the color's intended use: These tokens use descriptive names that convey the color's purpose within the design system.
- Examples:
  `bg-danger` (might be used for backgrounds highlighting danger)
  `text-primary` (might be used for primary text)
  `border-strong` (might be used for strong borders)
- Alternative names: Alias tokens, brand tokens, reference tokens

#### Component-Specific Tokens

- Combine semantic meaning with component scope: These tokens are more specific and define colors for individual UI components.
- Examples:
  `@ bg-button-danger` (might be the specific red used for danger buttons)
  `@ text-navigation—link` (might be the text color for navigation links)
  `@ border-checkbox` (might be the border color for checkboxes)
- Optional: Not all design systems utilize this layer.

### Color Naming Conventions

- Material Design: Uses a numeric suffix to indicate lightness levels (e.g., `red-50` for lightest, `red-900` for darkest).
- Atlassian: Uses letter-based suffixes (e.g., `b50` for a light shade, `b75` for a mid-tone).
- Ant Design: Employs a numeric suffix like Material Design, but starts from 1 instead of 50 (e.g., `red-1` for lightest, `red-6` for darkest).
- Orbit: Utilizes descriptive terms for different color states (e.g., `light`, `light:hover`, `light:active`).

| Orbit         | Atlassian | Material Design | Ant Design |
|---------------|-----------|-----------------|------------|
| light         | b50       | red-50          | red-1      |
| light:hover   | b75       | red-100         | red-2      |
| light:active  | b100      | red-200         | red-3      |
| normal        | -         | red-300         | red-4      |
| normal:hover  | -         | red-400         | red-5      |
| normal:active | -         | red-500         | red-6      |
| dark          | -         | red-600         | red-7      |
| dark:hover    | -         | red-700         | red-8      |
| dark:active   | -         | red-800         | red-9      |
| darker        | -         | red-900         | red-10     |

## Using Color Palette Effectively

1. Define Your Color Roles
   - Brand Color: The core color representing your brand, used consistently across all elements.
   - Supporting Colors: 2-3 colors that complement the brand color, adding depth and variety.
   - Neutrals: White, black, gray, and beige for backgrounds, text, and subtle accents.
2. Utilize the 60-30-10 Rule (Optional)
   - This is a popular guideline suggesting the following color distribution:
     - 60%: Primary color (dominant)
     - 30%: Secondary color (supporting)
     - 10%: Accent color (for emphasis)
   - It offers a balanced starting point, but don't be afraid to adjust based on your specific needs and design goals.
3. Consider the Purpose of the Element
   - Backgrounds: Use the shade of gray or a lighter supporting color for neutrality and maintaining readability.
   - Text: Ensure high contrast with the background color (ideally black or white on light backgrounds, and a contrasting dark gray on lighter backgrounds). Accessibility is crucial.
   - Primary Elements: Use the brand color or the dominant supporting color for key elements that demand attention, like buttons, headings, or call-to-actions.
   - Secondary Elements: Use the secondary supporting color for elements that complement the primary ones, like borders, icons, or subtle highlights.
   - Accents: Employ a small amount of the other supporting color for small elements like hover effects or specific details, adding visual interest without overwhelming the design.
4. Consider Color Harmony
   - Analogous: Colors next to each other on the color wheel, creating a sense of calmness and familiarity.
   - Complementary: Colors opposite each other on the wheel, offering high contrast and vibrancy, but use them sparingly to avoid overwhelming the viewer.
   - Triadic: Three colors evenly spaced on the wheel, offering a dynamic and visually interesting combination.
5. Prioritize Accessibility
   - Ensure sufficient contrast between text and background colors for people with visual impairments. Use online tools to check your palette's accessibility.
6. Test and Refine
   - View your color palette on various screens and lighting conditions to ensure it translates well across different mediums. Get feedback from others to gauge their perception and emotional response to the chosen colors.
7. Additional Tips
   - Limited Palette: Start with a limited color palette for a more unified look.
   - Hierarchy: Use color to create visual hierarchy, directing the viewer's attention to important elements.
   - Emotional Impact: Consider the emotions you want to evoke with your color choices. For example, blue often conveys trust, while red can represent excitement or urgency.
   - Context Matters: Adapt your color choices based on the specific context, target audience, and brand message.

### Other Guidelines

1. The Rule of Thirds
   - This principle suggests dividing your composition into thirds horizontally and vertically, creating nine equal sections. Placing elements along these intersections or the lines themselves can create a more balanced and aesthetically pleasing arrangement. You can then use your color palette strategically within these sections to further enhance the composition.
2. Color Contrast
   - Effective use of contrast between colors is essential for creating visual hierarchy, readability, and accessibility. Consider the following:
     - Lightness Contrast: This refers to the difference in lightness or darkness between two colors. Ensure sufficient contrast between text and background colors for people with visual impairments. Tools like WebAIM's Contrast Checker can help you assess accessibility.
     - Color Contrast: This refers to the inherent difference between two colors, regardless of lightness. Experiment with complementary colors (opposites on the color wheel) for high contrast, or analogous colors (next to each other) for a more subtle contrast.
3. The Tetrad Color Scheme
   - This scheme utilizes four colors evenly spaced on the color wheel, offering a dynamic and vibrant combination. While it can be visually engaging, it's crucial to carefully choose and balance the colors to avoid overwhelming the viewer.
4. Warm and Cool Colors
   - Colors can be broadly categorized as warm (reds, oranges, yellows) or cool (blues, greens, purples). Understanding their psychological impact can be helpful:
     - Warm colors: Often evoke feelings of energy, excitement, or passion. Use them sparingly in large areas and consider pairing them with cooler colors for balance.
     - Cool colors: Often associated with calmness, peace, or trust. They can be used more liberally as backgrounds or for large areas.
5. Analogous and Complementary Color Schemes
   - As mentioned before, these are established color harmonies:
     - Analogous: Colors next to each other on the color wheel, creating a sense of calmness and familiarity.
     - Complementary: Colors opposite each other on the wheel, offering high contrast and vibrancy. Use them sparingly to avoid overwhelming the viewer.
6. Hierarchy and Emphasis
   - Primary Emphasis: If you want a clear hierarchy where the brand color commands the most attention, use the other supporting color for secondary elements. This creates a balanced sense of importance.
   - Secondary Emphasis: If you want the chosen secondary color to have a slightly stronger presence alongside the brand color, you can use it for more elements compared to the remaining supporting color.
7. Desired Mood and Message
   - Calm and Cohesive: Choose colors that are analogous to the brand color on the color wheel. This creates a sense of harmony and familiarity.
   - Vibrant and Energetic: Opt for colors that are complementary to the brand color. This creates a high-contrast and attention-grabbing combination, but use it sparingly to avoid overwhelming the viewer.
   - Specific Emotions: Consider the psychological associations of different colors. For example, if your brand color is red (associated with excitement), using a contrasting cool green (associated with calmness) can create a sense of balance.
