.. index:: Search

..  _content_authors_search:

---------
Searching
---------


.. image:: /_static/images/page-toolbar-search.png
    :width: 50 %
    :align: center

.. image:: /_static/images/page-search.png
    :width: 95 %    
    :align: center

Search allows you to find objects in the system by filtering for them with keywords and canned filter options.

Filters.  By default (from the search box on the context nav) the filter is generic and provides basic cross cutting filters that allow you to augment a keyword search to find the content you want.  Filters are pluggable which means that it is possible to create custom filters that enable authors to quickly find specific kinds of content without needing to know how to use complete logical operators or construct queries.

Result Templates: Each result is a content type of one sort or another.  Crafter Studio uses a template to render each result.  If a custom template is found for a given type it will be used, otherwise a default result template is used.  When you are looking for content the information you can quickly see about that content has a lot to do with how good your search experience is.  Authors need to see different information for different types of content.  For example, with an article you may want to see the category, the publish date and the summary.   For a banner, you want to see the banner creative.

Result Selection: Note the checkboxes to the left of each result type.  Just as you can select multiple items on the dasboard and then interact with them in bulk, the same is true with search.  If you are in general search mode you will have checkboxes that allow you to choose many items and access to the context nav to take action on those items.  If you are selecting specific items for a control in a form you will be able to choose whatever number of items are expected by the control.  In selection mode you will note that the site context nav does not show.  A select/cancel bar shows at the bottom of search instead to confirm or cancel your selection.  If only one item is expected you will have radio buttons rather than checkboxes.

Search Pagination:  You can choose how many results you want to see per page.  Controls at the bottom of the page allow you to move through the results.

Sort controls:  Each filter can define what the sort controls are for that filter.  In general you will find things like

    * relevance,

    * alpha on title,

    * create date etc


.. TODO:: Update blurbs and images for authoring search.  The blurb above is from the wiki, for an older version of crafter cms
