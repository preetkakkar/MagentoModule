# Magento 2 full breadcrumbs with categories

This module enhances navigation by displaying the complete breadcrumb trail on product pages, including the full category hierarchy. The breadcrumbs show the path from the homepage through each category level, down to the current page, allowing users to understand their location within the store structure easily.

<strong>Key features:</strong><br />
<ul>
<li><strong>Detailed Navigation Path:</strong> Displays every category level from the homepage to the product, providing clear navigation.</li>
<li><strong>Enhanced User Experience:</strong> Helps users backtrack or explore related categories, improving site usability and encouraging further browsing.</li>
<li><strong>SEO Benefits:</strong> Creates a structured and consistent navigation trail that can improve search engine indexing and visibility.</li>
</ul>

<strong>Enable ‘Use Categories Path for Product URLs’</strong><br />
In the Magento Admin panel, ensure that the setting to include the category path in URLs is enabled: <br />
Go to Stores > Configuration > Catalog > Catalog > Search Engine Optimization.<br />
Set Use Categories Path for Product URLs to Yes.

<strong>Add module to app/code/MagentoModule</strong>

<strong>Magento Commands</strong><br />
php bin/magento setup:upgrade<br />
php bin/magento setup:compile<br />
php bin/magento cache:clean<br />


<strong>Add/Update breacrumbs file in theme</strong><br />
app/design/frontend/vendor/theme/Magento_Catalog/templates/product/breadcrumbs.phtml

<strong>Example of breadcrumbs below</strong><br /> 
Home > Category > Sub Category > Product <br />
