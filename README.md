<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LiteImage SEO Optimizer - WordPress Plugin</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f8f9fa;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .header h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            font-weight: 700;
        }
        
        .header p {
            font-size: 1.3rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto;
        }
        
        .main-content {
            background: white;
            margin: 40px 0;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .section {
            padding: 40px;
            border-bottom: 1px solid #eee;
        }
        
        .section:last-child {
            border-bottom: none;
        }
        
        .section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #2c3e50;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .section h3 {
            font-size: 1.5rem;
            margin: 30px 0 15px;
            color: #34495e;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }
        
        .feature-card {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }
        
        .feature-card h4 {
            color: #2c3e50;
            margin-bottom: 10px;
            font-size: 1.2rem;
        }
        
        .feature-list {
            list-style: none;
            margin: 20px 0;
        }
        
        .feature-list li {
            padding: 8px 0;
            position: relative;
            padding-left: 25px;
        }
        
        .feature-list li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #27ae60;
            font-weight: bold;
        }
        
        .screenshots {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .screenshot {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
        }
        
        .screenshot img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .screenshot p {
            margin-top: 10px;
            font-weight: 500;
            color: #666;
        }
        
        .faq-item {
            margin: 20px 0;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 8px;
        }
        
        .faq-item h4 {
            color: #2c3e50;
            margin-bottom: 10px;
        }
        
        .installation-steps {
            background: #e8f4fd;
            padding: 25px;
            border-radius: 8px;
            margin: 20px 0;
        }
        
        .installation-steps ol {
            margin-left: 20px;
        }
        
        .installation-steps li {
            margin: 10px 0;
        }
        
        .highlight-box {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            border-radius: 10px;
            margin: 30px 0;
            text-align: center;
        }
        
        .highlight-box h3 {
            margin-bottom: 15px;
            color: white;
            font-size: 1.8rem;
        }
        
        .emoji {
            font-size: 1.5rem;
        }
        
        .code {
            background: #2c3e50;
            color: #ecf0f1;
            padding: 15px;
            border-radius: 5px;
            font-family: 'Courier New', monospace;
            margin: 10px 0;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .section {
                padding: 20px;
            }
            
            .features-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="container">
            <h1>LiteImage SEO Optimizer</h1>
            <p>A powerful, all-in-one WordPress plugin that dramatically improves site performance and SEO by optimizing your images and enhancing accessibility.</p>
        </div>
    </div>

    <div class="container">
        <div class="main-content">
            <div class="section">
                <h2><span class="emoji">🚀</span> Overview</h2>
                <p>LiteImage SEO Optimizer is more than just an image compressor. It's a full suite of tools designed to make your site faster, more accessible, and more search-engine friendly.</p>
                
                <div class="highlight-box">
                    <h3>Transform Your WordPress Site Performance</h3>
                    <p>Reduce image file sizes by up to 90%, improve Core Web Vitals, and enhance accessibility with our comprehensive optimization suite.</p>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">⚡</span> Image & Performance Optimization</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <h4>Smart Compression</h4>
                        <p>Automatically compress JPEGs, PNGs, and GIFs with multiple levels of quality (Balanced, Aggressive, etc.) without significant visual loss.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Lossless Option</h4>
                        <p>Use lossless tools like <code>jpegtran</code> and <code>optipng</code> for perfect pixel quality when needed.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Automatic Resizing</h4>
                        <p>Set maximum width and height limits to prevent users from uploading oversized images that slow down your site.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Next-Gen Formats</h4>
                        <p>Automatically convert images to <strong>WebP</strong> and <strong>AVIF</strong> formats and serve them to supported browsers using <code>&lt;picture&gt;</code> elements.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Lazy Loading</h4>
                        <p>Improve Core Web Vitals and perceived load time by enabling native lazy loading for below-the-fold images.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Backup & Restore</h4>
                        <p>Keep a backup of all original images, allowing you to revert changes or re-optimize with different settings at any time.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">🛠️</span> Workflow & Management</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <h4>Bulk Optimizer</h4>
                        <p>Process your entire existing Media Library in batches with a user-friendly interface that shows real-time progress.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Single Image Optimization</h4>
                        <p>Optimize individual images directly from the Media Library with one click.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Settings Control</h4>
                        <p>A centralized settings page to control every aspect of optimization, from image dimensions to lazy loading.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Reset Functionality</h4>
                        <p>A one-click option to clear all optimization data and restore original images if you need to start fresh.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">📊</span> Reporting, Auditing & SEO</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <h4>Dashboard Widget</h4>
                        <p>Get an at-a-glance summary of your optimization stats and recent activity right on your WordPress dashboard.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Reports & Logs</h4>
                        <p>A dedicated reports page with a detailed activity log of all optimization tasks, which can be filtered and exported as a CSV.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Accessibility Audits</h4>
                        <p>Scan your media library for common accessibility issues, including missing alt text, contrast issues, and large images.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Automatic Alt Text</h4>
                        <p>Automatically generate SEO-friendly alt text for new uploads that are missing it, using the filename as a source.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">🛒</span> WooCommerce Integration</h2>
                <p>Supercharge your e-commerce store with dedicated tools for product image optimization and SEO.</p>
                <div class="features-grid">
                    <div class="feature-card">
                        <h4>Product Image & Gallery Optimization</h4>
                        <p>Automatically optimizes main product images and gallery images upon upload and via a dedicated bulk optimizer.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Product Page SEO Score</h4>
                        <p>Get a real-time SEO score and a checklist of improvements right on the WooCommerce product edit screen.</p>
                    </div>
                    <div class="feature-card">
                        <h4>Alt Text from Product Titles</h4>
                        <p>Improve your product's search engine visibility by automatically generating `alt` text from the WooCommerce product title.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">🖼️</span> Screenshots</h2>
                <div class="screenshots">
                    <div class="screenshot">
                        <img src="https://clintsax.getbetterguide.net/wp-content/uploads/2025/06/dashboard.png" alt="Dashboard Widget">
                        <p>Dashboard Widget</p>
                    </div>
                    <div class="screenshot">
                        <img src="https://clintsax.getbetterguide.net/wp-content/uploads/2025/06/bulk-optimize-1.png" alt="Bulk Optimization">
                        <p>Bulk Optimization UI</p>
                    </div>
                    <div class="screenshot">
                        <img src="https://clintsax.getbetterguide.net/wp-content/uploads/2025/06/bulk-optimize.png" alt="Settings Page">
                        <p>Detailed Settings Page</p>
                    </div>
                    <div class="screenshot">
                        <img src="https://clintsax.getbetterguide.net/wp-content/uploads/2025/06/media-library.png" alt="Media Library">
                        <p>Media Library Integration</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">⚙️</span> Installation</h2>
                <div class="installation-steps">
                    <ol>
                        <li>Upload the <code>liteimage-seo-optimizer</code> folder to the <code>/wp-content/plugins/</code> directory.</li>
                        <li>Activate the plugin through the 'Plugins' menu in WordPress.</li>
                        <li>Go to <strong>LiteImage SEO > Settings</strong> to configure your preferred optimization levels. We recommend keeping the defaults for balanced performance.</li>
                        <li>Navigate to <strong>LiteImage SEO > Bulk Optimize</strong> to process all your existing images.</li>
                    </ol>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">❓</span> Frequently Asked Questions</h2>
                
                <div class="faq-item">
                    <h4>What image formats does the plugin optimize?</h4>
                    <p>The plugin can read and optimize JPEG, PNG, and GIF images. It can also create WebP and AVIF versions of these images.</p>
                </div>

                <div class="faq-item">
                    <h4>Will this slow down my website during optimization?</h4>
                    <p>No. Bulk optimization is handled via client-driven AJAX requests that process one image at a time to prevent server overload. Your site will remain fast and responsive for users during the process.</p>
                </div>

                <div class="faq-item">
                    <h4>Can I revert to my original images?</h4>
                    <p>Yes. As long as the "Backup Original Images" setting is enabled (which it is by default), you can use the "Reset All Optimizations" feature to restore your original, untouched images.</p>
                </div>

                <div class="faq-item">
                    <h4>How does lazy loading work?</h4>
                    <p>The plugin intelligently adds the <code>loading="lazy"</code> attribute to images that are determined to be "below the fold." It avoids adding this to critical images like logos, banners, or the first few images in a post to ensure your Largest Contentful Paint (LCP) score is not negatively affected.</p>
                </div>

                <div class="faq-item">
                    <h4>Is this plugin compatible with my theme and other plugins?</h4>
                    <p>LiteImage SEO Optimizer is built to WordPress coding standards and should be compatible with most themes and plugins. It uses standard filters and hooks to apply its features.</p>
                </div>

                <div class="faq-item">
                    <h4>What accessibility features are included?</h4>
                    <p>The plugin includes an accessibility audit that scans for missing alt text, potential contrast issues, oversized images, and missing captions. It can automatically fix some issues like missing alt text and large images.</p>
                </div>

                <div class="faq-item">
                    <h4>Does the bulk optimizer respect my settings?</h4>
                    <p>Yes, the bulk optimizer loads and applies all your user-defined settings for resizing, compression, format conversion, and backups.</p>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">🎯</span> Key Benefits</h2>
                <ul class="feature-list">
                    <li><strong>Improved Page Speed:</strong> Reduce image file sizes by up to 90% for faster loading times</li>
                    <li><strong>Better SEO:</strong> Automatic alt text generation and accessibility improvements</li>
                    <li><strong>Enhanced User Experience:</strong> Faster page loads and better Core Web Vitals scores</li>
                    <li><strong>Accessibility Compliance:</strong> Built-in auditing and automatic fixes for common issues</li>
                    <li><strong>Modern Format Support:</strong> WebP and AVIF conversion for optimal browser performance</li>
                    <li><strong>Easy Management:</strong> Bulk operations and comprehensive reporting</li>
                    <li><strong>Safe & Reversible:</strong> Backup original images and easy restoration options</li>
                    <li><strong>WooCommerce Ready:</strong> Full compatibility with WooCommerce stores</li>
                </ul>
            </div>

            <div class="section">
                <h2><span class="emoji">📋</span> System Requirements</h2>
                <ul class="feature-list">
                    <li>WordPress 5.6 or higher</li>
                    <li>PHP 7.4 or higher</li>
                    <li>GD Library or Imagick extension (recommended)</li>
                    <li>WebP support for next-gen format conversion</li>
                    <li>AVIF support (PHP 8.1+ required for AVIF conversion)</li>
                </ul>
                <div class="highlight-box" style="background: #f39c12; margin-top: 20px; text-align: left;">
                    <h4 style="color: white;">Note for Large Sites</h4>
                    <p style="color: white; opacity: 1;">For websites with a very large number of images or on shared hosting environments, we recommend ensuring your server has a `max_execution_time` of at least 300 seconds and a `memory_limit` of 256M or higher for the most reliable bulk optimization experience.</p>
                </div>
            </div>

            <div class="section">
                <h2><span class="emoji">🔄</span> Changelog</h2>
                <h3>Version 1.0.0</h3>
                <ul class="feature-list">
                    <li>Initial release with core image optimization features</li>
                    <li>Smart compression with multiple quality levels</li>
                    <li>WebP and AVIF format conversion</li>
                    <li>Bulk optimization with progress tracking</li>
                    <li>Dashboard widget and statistics</li>
                    <li>Settings page with comprehensive controls</li>
                    <li>Accessibility auditing and reporting</li>
                    <li>Lazy loading implementation</li>
                    <li>Backup and restore functionality</li>
                    <li>WooCommerce compatibility</li>
                    <li>CSV export for reports</li>
                    <li>Automatic alt text generation</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html> 
