# Magento2 import / export sample files

<p>In this repository we have gathered all sample files for Magento 2 import and export procedures. Every file has been tested with the different Magento 2 versions and latest release of <b><a href="https://firebearstudio.com/the-improved-import.html">Improved Import and Export extension</a></b>.</p>
<p align="center" />If you are new to the import process - start by reading <b><a href="https://firebearstudio.com/blog/the-complete-guide-to-magento-2-product-import-export.html">FireBear Studio Magento 2 import guide</a></b>.</p>
<h2>List of Magento 2 sample import files</h2>
<b><a href="https://github.com/firebearstudio/magento2-import-export-sample-files/tree/master/Improved%20Import%20:%20Export%20-%20Sample%20Files" />/Improved Import : Export - Sample Files</a></b>
<ul>
  <li><b>advanced_pricing.csv .xml .json</b> - a native Magento 2 file composition for importing tier prices. Comes with only product SKUs and tier price attributes: <i>tier_price_website, tier_price_customer_group, tier_price_qty, tier_price, tier_price_value_type</i>. These composition is enough to update advanced pricing for existing Magento 2 products.</li>
  <li><b>cart_price_rules.csv .xml .json</b> - a sample file for importing cart price rules to Magento 2 with Improved Import and Export extension. If the file you will find three price rules with different sample coupon codes, discountss and other attributes.</li>
  <li><b>categories.csv .xml .json</b> - a sample file for importing Categories to Magento 2 with Improved Import and Export extension. There are three sample categories you can quickly identify. Each category comes with different settings to show you possible attribute values.</li>
  <li><b>cms_pages.csv .xml .json</b> - a sample file with CMS blocks that can be imported to Magento 2 with Improved Import and Export extension. Useful when migrating from an old store. Two sample CMS blocks help you understand how to import different settings and attributes and what values Magento 2 accepts.</li>
  <li><b>customer_addresses.csv .xml .json</b> - a native Magento 2 file composition for importing customer addresses. First of three customer import files with the same sample customers for clarity. In this file you can find sample data on which address values can be accepted by Magento 2.</li>
  <li><b>customers_and_addresses.csv .xml .json</b> - a native Magento 2 file composition for importing customers and addresses. Second customer file. Here you can get idea how to import both, customer data and addresses with different attribute values for every customer.</li>
  <li><b>customers_main.csv .xml .json</b> - a native Magento 2 file composition for importing customers. Third customer file. It helps you get the idea of main customer attributes, how to fill them and what is the file composition accepted by Magento 2.</li>
  <li><b>fixed_product_tax.csv .xml .json</b> - a native Magento 2 file for importing products. The main difference is the Magento 2 Fixed Product Tax attribute that allows you to add tax per product for different countries. In this file you can see which fixed product tax values can be imported.</li>
  <li><b>products_all_types.csv .xml .json</b> - a sample file which lists ALL product types for Magento 2 import. In this file you can find products of every possible type: configuable, bundle, grouped, downloadable etc. You can learn which attributes are required to import every product type and what values are expected in these attributes.</li>
  <li><b>products_and_advanced_pricing.csv .xml .json</b> - a sample file which allows to import products along with tier prices using Improved Import and Export Magento 2 extension. Default Magento 2 import only allows to import tier prices and products in separate files. With this file you get a sample of new attribute <i>tier_priceS</i> only available for Improved Import. Use this file with entity 'Products' to import tier prices.</li>
  <li><b>products_bundle.csv .xml .json</b> - a sample file with Magento 2 bundle product import. Here you can find bundle products and learn what attributes and values are required to import bundle products. The file can be imported with default Magento 2 import.</li>
  <li><b>products_configurable_improved.csv .xml .json</b> - a sample file for importing Magento 2 configurable products in a new, straightforward, way. Only for Improved Import extension. In this file we use custom attribute column 'group' where we list parent product dependency for simple products. Using Improved Import extension you only need to specify this 'group' attribute, and the extension will assign simple products automatically.</li>
  <li><b>products_configurable_native.csv .xml .json</b> - a native Magento 2 file for importing configurable products. In this file you can find default Magento 2 table composition for importing configurable products using attributes <i>configurable_variations</i> and <i>additional_attributes</i>.</li>
  <li><b>products_grouped.csv .xml .json</b> - a sample file with Magento 2 grouped product import. Here you can find grouped products and learn what attributes and values are required to import grouped products. The file can be imporeted with default Magento 2 import.</li>
  <li><b>tax_rates.csv</b> - a sample file for importing Magento 2 taxes. Only available in CSV as default Magento 2 import process is used. In this file you will learn table composition for importing taxes applied to different stores and store views. To import taxes proceed to <b>System > Import and Export Tax Rates</b> in your Magento 2 admin panel.</li>
  <li><b>update_price_stock.csv .xml .json</b></li> - a sample file for updating Magento 2 product stock and price. Use with Improved Import. In this file we share an example of how you can quickly compose a file for updating stock and price. You only need to specify product SKU, Price and Qty attributes. This way if your supplier provides you with the updates, you can apply them quickly.</li>
</ul>
<p align="center" />Up to date default <a href="https://github.com/magento/magento2/">Magento 2 Open Source (CE) & Commerce (EE, Cloud) import</a> / export CSV files &amp; sample files for <a href="https://firebearstudio.com/the-improved-import.html" title="Magento 2 Import & Export">Firebear Improved Import / Export extension</a> (CSV, XML, Json)</p>

<h2><a href="https://firebearstudio.com/the-improved-import.html">Imroved Import and Export extension for Magento 2</a></h2>
<ul>
  <li>If you are looking for the way to automate import and export procedures</li>
  <li>If you want to import from XML, CSV or Json files</li>
  <li>If you need to map attributes and categories</li>
  <li>If you require order, category, cart price rule import</li>
</ul>
<a href="https://firebearstudio.com/the-improved-import.html" title="Magento 2 Import Guide"><img src="https://firebearstudio.com/media/catalog/product/cache/1/small_image/040ec09b1e35df139433887a97daa66f/m/a/magento2importflow.png" /></a>

<h3>What is the extension</h3>
<ul>
  <li><b>Improved Import and Export is a Magento 2 extension</b> - meaning all the management process takes place in the administrator panel. You are not tied to the third party applications and don't have to run anything in the background.</li>
  <li><b>The extension is open code</b> - meaning that you can make necessary code adjustments and even improve existing functionality the way you like.</li>
  <li><b>Customization endpoints</b> - FireBear team have composed a dedicated customization module for Improved Import and Export extension you can use to enhance the extension's functionality.</li>
  <li><b>Json file support</b> - a first step to Rest API integration with any software you are using for customer or sales management. Try integrating your CRM, ERP or POS systems to the extension.</li>
</ul>
<p align="center" /><a href="https://firebearstudio.com/blog/the-complete-guide-to-magento-2-product-import-export.html" title="Magento 2 Import Guide">Magento 2 Ultimate Import & Export guide</a></p>

<p align="center" /><a href="https://firebearstudio.com/the-improved-import.html" title="Magento 2 Import Guide"><img src="https://firebearstudio.com/blog/wp-content/uploads/2016/06/import-mapping-cron-magento2.png" /></a></p>

<h3>Magento 2 Google Sheets import</h3>

<p>Improved Import and Export extension for Magento 2 allows importing CSV files directly from the Google Sheets. You can edit the file with your colleagues or supplier, paste it into the import job and schedule it to run automatically.</p>
<p align="center" /><a href="https://firebearstudio.com/blog/magento-2-google-sheet-import.html" title="Magento 2 Google Sheet Import
">Read more about Magento 2 Google Sheet Import</a></p>
<p>We have also composed a Master Google Sheet table for Magento 2 where gathered all possible import entities. Every attribute comes with a description and samples. Feel free adding it to your Google Drive and using for your store.</p>
<p align="center" /><a href="https://docs.google.com/spreadsheets/d/13FemIzzexF5koAdQYjbcKscqoCfXyknYWkQkbSZGPsk/edit#gid=1164219475" title="Google Sheet Master Table for Magento 2 Import">Google Sheet Master Table for Magento 2 Import</a></p>

<a href="https://docs.google.com/spreadsheets/d/13FemIzzexF5koAdQYjbcKscqoCfXyknYWkQkbSZGPsk/edit#gid=1164219475" title="Magento 2 Google Sheet Import
"><img src="https://i.imgur.com/hxXZrKf.png" /></a>

<h2>Magento 2 Improved Import and Export Roadmap</h2>
<ul>
<li>Full REST API support - import any XML or JSON data from REST API with automatic authorization, data mapping, and processing. Establish flexible connection to any system.</li>
<li>Import and export events and job queue and restrictions - build flexible conditions for running import and export jobs after any Magento 2 update, queue jobs, automatically block jobs that depend on any system event or process. For example: order placed, new product or customer created, attribute modified. </li>
<li>Duplicate import and export jobs, jobs settings, configuration and other.</li>
<li>Magento 2 product image processing settings and configuration - crop and scale, adjust size and files name, convert to different format, compression and performance optimization.</li>
<li>Email, WhatsApp, Telegram and other notification possibilities for jobs - send status and debug information about import and export processes.</li>
<li>Import diff system – a smart algorithm for comparing the current state of Magento 2 and data in the specified import source. Save time and resources by updating only relevant data.</li>
<li>Imports job filtering - flexible rules and conditions for updating and importing specific data from any source.</li>
<li>FireBear Composer repository - for extension installation and upgrade with Composer package manager.</li>
<li>Simplified and improved import of bundle and grouped products – import and create on the fly complex products by the fields of the child products.</li>
<li>Full support of Magento 2 Multiple Source Inventory extension and its workflow.</li>
<li>Full support and compatibility with Magento 2 B2B and Omnichannel.</li>
<li>Price and currency formatting.</li>
<li>Get raw SQL query of import & export job to run and adjust directly to Mageto 2 MySQL server.</li>
<li>Dry Run (Test import) - preview and test imported data without actual import. Useful for debugging and catching issues before import.</li>
<li>Full circle Magento 2 integration and synchronization of products and orders with top drop-shipping providers (Doba, Dropship Direct, Wholesale2b, Aliexpress, Taobao, Alibaba etc. more details at <a href=”https://firebearstudio.com/blog/ultimate-list-of-drop-shipping-platforms-and-integrations.html” />Ultimate List Of Drop Shipping Platforms And Integrations</a>). </li>
</ul>

