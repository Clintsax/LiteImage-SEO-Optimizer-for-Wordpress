# LiteImage SEO Optimizer

A powerful, all-in-one WordPress plugin that dramatically improves site performance and SEO by optimizing your images and enhancing accessibility.

## Key Features

LiteImage SEO Optimizer is more than just an image compressor. It's a full suite of tools designed to make your site faster, more accessible, and more search-engine friendly.

### 🚀 Image & Performance Optimization
- **Smart Compression**: Automatically compress JPEGs, PNGs, and GIFs with multiple levels of quality (Balanced, Aggressive, etc.) without significant visual loss.
- **Lossless Option**: Use lossless tools like `jpegtran` and `optipng` for perfect pixel quality when needed.
- **Automatic Resizing**: Set maximum width and height limits to prevent users from uploading oversized images that slow down your site.
- **Next-Gen Formats**: Automatically convert images to **WebP** and **AVIF** formats and serve them to supported browsers using `<picture>` elements for maximum compatibility.
- **Lazy Loading**: Improve Core Web Vitals and perceived load time by enabling native lazy loading for below-the-fold images, with smart exclusion for critical, above-the-fold content.
- **Backup & Restore**: Keep a backup of all original images, allowing you to revert changes or re-optimize with different settings at any time.

### 🛠️ Workflow & Management
- **Bulk Optimizer**: Process your entire existing Media Library in batches with a user-friendly interface that shows real-time progress.
- **Single Image Optimization**: Optimize individual images directly from the Media Library.
- **Settings Control**: A centralized settings page to control every aspect of optimization, from image dimensions to lazy loading.
- **Reset Functionality**: A one-click option to clear all optimization data and restore original images if you need to start fresh.

###  WooCommerce Integration
- **Product Image Optimization**: Automatically optimizes main product images and gallery images.
- **SEO Score for Products**: Adds a real-time SEO score and optimization checklist directly in the WooCommerce product edit screen.
- **Product-Based Alt Text**: Automatically generate `alt` text from the WooCommerce product title to improve product discoverability in image search.
- **Dedicated Bulk Optimizer**: A separate bulk optimization tool specifically for WooCommerce products to quickly process your entire catalog.

### 📊 Reporting, Auditing & SEO
- **Dashboard Widget**: Get an at-a-glance summary of your optimization stats and recent activity right on your WordPress dashboard.
- **Reports & Logs**: A dedicated reports page with a detailed activity log of all optimization tasks, which can be filtered and exported as a CSV.
- **Accessibility Audits**: Scan your media library for common accessibility issues, including:
    - Images with missing `alt` text.
    - Images with potential low-contrast issues.
    - Large images that need resizing.
    - Images missing captions.
- **Automatic Alt Text**: Automatically generate SEO-friendly alt text for new uploads that are missing it, using the filename as a source.

## Installation

1. Upload the `liteimage-seo-optimizer` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to **Litemage SEO > Settings** to configure your preferred optimization levels. We recommend keeping the defaults for balanced performance.
4. Navigate to **Litemage SEO > Bulk Optimize** to process all your existing images.

## Frequently Asked Questions

**What image formats does the plugin optimize?**
The plugin can read and optimize JPEG, PNG, and GIF images. It can also create WebP and AVIF versions of these images.

**Will this slow down my website during optimization?**
No. Bulk optimization is handled via client-driven AJAX requests that process one image at a time to prevent server overload. Your site will remain fast and responsive for users during the process.

**Can I revert to my original images?**
Yes. As long as the "Backup Original Images" setting is enabled (which it is by default), you can use the "Reset All Optimizations" feature to restore your original, untouched images.

**How does lazy loading work?**
The plugin intelligently adds the `loading="lazy"` attribute to images that are determined to be "below the fold." It avoids adding this to critical images like logos, banners, or the first few images in a post to ensure your Largest Contentful Paint (LCP) score is not negatively affected.

**Is this plugin compatible with my theme and other plugins?**
LiteImage SEO Optimizer is built to WordPress coding standards and should be compatible with most themes and plugins. It uses standard filters and hooks to apply its features.

## Troubleshooting

**The bulk optimizer gets stuck or times out.**
On servers with limited resources or when optimizing a very large number of images, the process can sometimes time out. While the plugin is designed to be as efficient as possible, you can improve its reliability by asking your web host to increase the following PHP settings:
*   `max_execution_time` to `300` (5 minutes)
*   `memory_limit` to `256M` or `512M`

These changes will give the server more time and memory to process each image, preventing crashes.

## Screenshots

1. **Dashboard Widget**
   ![Dashboard showing optimization statistics and quick actions](assets/screenshots/dashboard.png)

2. **Bulk Optimization UI**
   ![Bulk optimization interface with progress tracking](assets/screenshots/bulk-optimize.png)

3. **Detailed Settings Page**
   ![Plugin settings with various optimization options](assets/screenshots/settings.png)

4. **Media Library Integration**
   ![Media library with optimization status indicators](assets/screenshots/media-library.png)

## Support

For support or feature requests, please open an issue on our project's GitHub repository.

## License

GPL v2 or later
