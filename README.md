MephistoGoogleSiteMap
=====================

The Mephisto SiteMap Plugin creates an XML sitemap as specified by the SiteMap protocol (http://www.sitemaps.org/protocol.php) out of your mephisto installations article data.

Configuration
-------------

1. Point your web browser to your Mephisto installations plugin administration interface for this plugin (e.g. http://mysite.com/admin/plugins/show/sitemap).
2. Set the "Site uri" option to your web site's root url (e.g. http://mysite.com).
3. That's it, there is no step 3.

Other optional attributes you can change in MephistoGoogleSiteMap to affect how you inform google to index your site are:

    Home frequency    # the frequency of indexing your home page (plugin default is daily)
    Blog frequency    # the frequency of indexing a blog based page (plugin default is daily)
    Page frequency    # the frequency of indexing a page page (plugin default is weekly)
    Home priority     # priority of your sites index page to google's bot (plugin default is 0.9)
    Article priority  # priority of all other pages to google's bot (plugin default is 0.5)

To learn more about the values and properties these attributes represent, see:

http://www.sitemaps.org/protocol.php#xmlTagDefinitions

Inform the Search Engines
-------------------------

finally, for any of this to be useful, you'll want to ensure the various search engines are notified of the presence of your sitemap (which will be at http://your.domain.com/sitemap.xml).  You can learn more about notifying search engines of your sitemaps location here:

http://www.sitemaps.org/protocol.php#informing
