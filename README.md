# <https://arsham-website.azurewebsites.net>
2020 MSA Azure &amp; Cloud Fundamentals bootcamp submission report


## Front-end page builder plugin
My new website currently has the default WordPress blog layout with Twenty Nineteen theme pre-installed. I need a plugin to allow me to add a template to my site so that it can have some better design. This thereby improves the site's UI for any visitors.

I will use a front-end page builder plugin to do this as they allow users to create, edit, and customize their website layout without writing any code.

I chose Elementor over other front-end page builder plugins since it allows me to control every aspect of my site's design, and it is simple to use and flexible. Also, with over 5 million users, it is tried and tested.

### Implementation steps
  1. On the WordPress dashboard, go to ‘Plugins’ > ‘Add new’, and enter ‘Elementor’ in the search bar. Then click the ‘Install’ button, and then the ‘activate’ button.
  2. Go to ‘Pages’ > ‘Add new’. Then, click the ‘Edit with Elementor’ button.
  3. Inside the Elementor editor, click ‘Add template’ and choose one.
  4. To make the page in Elementor full width, go to Section > Layout, and switch 'Stretch Section' to 'Yes'.
  5. Rename the header, sub-headings, and captions.
  6. Edit the icons and links of the icon list at the bottom of the page. 
  7. Add a Google Maps widget then set the location and zoom.
  8. Adjust the top and bottom margins of the header and icon list.

The Elementor plugin satisfactorily added a clean and simple design which is responsive based on the viewing device. This resulted in a more pleasing UX and proffesional UI. Viewers are likely to spend more time engaging with the site resulting in increased site traffic.


## SEO plugin
Currently, I am not able to search for my site on a search engine using keywords in its address. I would assume others would have similar difficulties thus impeding on the traffic to my site. I need a plugin to increasing the quantity and quality of traffic to your website through organic search engine results.

I will use a Search Engine Optimization plugin to do this. SEO plugins optimize websites to make them reach a high position in Google’s – or another search engine’s – search results.

I chose Yoast SEO as it uses holistic SEO practices which focus on sustainable long-term strategies as opposed to tricking search engines.

### Implementation steps
  1. On the WordPress dashboard, go to ‘Plugins’ > ‘Add new’, and enter ‘Yoast SEO’ in the search bar. Then click the ‘Install’ button, and then the ‘activate’ button.
  2. On the left-hand side of the dashboard, in that menu, click on ‘SEO’ then click on 'Yoast SEO configuration wizard' and run through the wizard.

Immediately after completing the wizard, I am not able to see a difference when I search for my site on Google.


## Cache managment plugin
My site is currently a bit slow to load after entering its URL. I need a plugin to improve the performance of my website.

I will use a cache managment plugin to do this. A caching plugin generates static HTML pages of my website and saves it on my Azure server. Each time a user tries to access my website, the caching plugin serves up the lighter HTML page instead of processing the comparatively heavier WordPress PHP scripts thus resulting in faster loading speed.

I chose WP-Optimize as their cache feature is built around the world’s fastest caching engine. It optimizes my website by allowing me to clean and optimise my database. It gives me the option to compress my images. It allows me cache my pages, for super fast load times

### Implementation steps
  1. On the WordPress dashboard, go to ‘Plugins’ > ‘Add new’, and enter ‘WP-Optimize’ in the search bar. Then click the ‘Install’ button, and then the ‘activate’ button.
  2. On the left-hand side of the dashboard, in that menu, click on ‘WP-Optimize’.
    a. Click on the 'Database' menu then click 'Run all selected optimizations' under 'Optimization' and wait for the plugin to clean your database.
    b. Click on the 'Images' menu then click 'Select all' under 'Uncompressed images' then click 'Compress the selected images' and wait for the plugin to compress your images.
    c. Click on the 'Cache' menu then switch the 'Enable page caching' toggle to on.

Before using WP-Optimize, according to Google's PageSpeed Insights, my site recieved a score of 36/100 for its performance. After using WP-Optimize, my site recieved a score of 55/100 showing an improvment as a result of the cache managment plugin.


## Analytics plugin
Currently, I am not able to track traffic and user behaviour on my site to see how much it is being accessed and in what ways.

I will use an analytics plugin to enable me to do this. An analytics plugin allows you to get all your site's data, metrics, and insights without leaving your WordPress dashboard. The majority of users choose Google Analytics. While Google Analytics is a powerful option, many find the sheer amount of data available on GA daunting, and the interface clunky. WordPress plugins aim to simplify the interface so that users get to the data they need without feeling overwhelmed.

I chose MonsterInsights since it allows you to enable all advanced Google analytics tracking features with just a few clicks as opposed to requiring developer knowledge to enable. MonsterInsights also keeps up with all Google Analytics updates and shows real time stats directly in the WordPress dashboard.

### Implementation steps
  1. On the WordPress dashboard, go to ‘Plugins’ > ‘Add new’, and enter ‘MonsterInsights’ in the search bar. Then click the ‘Install’ button, and then the ‘activate’ button.
  2. On the left-hand side of the dashboard, in that menu, click on ‘Insights’ then click on 'Launch the Wizard!' and run through the wizard.
  3. During the wizard, link MonsterInsights with your Google Analytics account.
  4. View all analytics on your WordPress dashboard.

On my WordPress dashboard I can now track stats such as sessions and page views.
