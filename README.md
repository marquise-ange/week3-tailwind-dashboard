## How I Customized Tailwind

I customized Tailwind CSS to create a clean, modern, and responsive MediFind Admin Dashboard. I extended the default theme with a custom brand color palette using shades of teal and dark blue to give the dashboard a professional appearance. I also selected a custom font to improve readability and maintain consistent typography throughout the interface.

To make my code more organized and reusable, I created custom component classes in my Tailwind CSS entry file using `@apply` inside `@layer components`. These include `.btn-primary` for consistent button styling, `.card` for dashboard cards and panels, and `.nav-link` for sidebar navigation links. These reusable classes help reduce repeated utility classes and make the HTML easier to maintain.

I used Tailwind's responsive utilities, including `sm:`, `md:`, `lg:`, and `xl:`, to make the dashboard adapt to different screen sizes. I also added hover, focus, and transition utilities to improve user interaction. Finally, I implemented a CSS-based light and dark theme switcher to make the interface more flexible and comfortable to use.