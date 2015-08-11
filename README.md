# Magento-URL-Rewrite
Fix duplicated and trash rewrites in default Magento URL rewrite system (core_url_rewrite table)

This is just local rewrite of app/code/local/Mage/Catalog/Model/Url.php - copy to your Magento root folder, clean cache and run catalog url reindex. 

More details about Magento URL rewrite duplicates
- <a href="http://magento.stackexchange.com/questions/17553/magento-core-url-rewrite-table-excessively-large">Magento core_url_rewrite table excessively large<a/>
- <a href="http://firebearstudio.com/blog/magento-url-reindex-core_url_rewrite-duplicates-patch.html">Magento URL reindex (core_url_rewrite) duplicates patch</a>
- <a href="https://github.com/magento/bugathon_march_2013/issues/265">Catalog url rewrites and duplicate url_keys.</a>
- Created based on <a href="https://gist.github.com/edannenberg/5310008">Fixes the catalog url rewrite indexer in Magento 1.7.x-1.9.x</a>
- <a href="http://www.atwix.com/magento/duplicated-product-url-keys-in-community-edition/">Duplicated product URL keys in Magento Community Edition</a> (there is another solution described)
- Magento Enterprise patch whic fix the same <a href="https://gist.github.com/piotrekkaminski/c348538ca91ba35773be">PATCH_SUPEE-389_EE_1.12.0.2_v2.sh</a>
