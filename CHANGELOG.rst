Changelog
=========

v1.0.0 (2019-11-11)
-------------------

-  Update documentation site. (`#49 <https://github.com/treasure-data/pytd/pull/49>`__, `#57 <https://github.com/treasure-data/pytd/pull/57>`__)
-  Add Treasure Data API endpoint HTTPS scheme validation. (`#51 <https://github.com/treasure-data/pytd/pull/51>`__)
-  Support bulk importing with the MessagePack format. (`#53 <https://github.com/treasure-data/pytd/pull/53>`__)
-  Improve stability of ``BulkImportWriter`` session ID. (`#55 <https://github.com/treasure-data/pytd/pull/55>`__)
-  Require td-client-python version 1.1.0 or later. (`#56 <https://github.com/treasure-data/pytd/pull/56>`__)
-  Add ``Client#exists(database, table)`` and ``Client#create_database_if_not_exists(database)`` method. (`#58 <https://github.com/treasure-data/pytd/pull/58/>`__)


v0.8.0 (2019-09-17)
-------------------

-  Clean up docstrings and launch documentation site.
   (`#43 <https://github.com/treasure-data/pytd/pull/43>`__, `#44 <https://github.com/treasure-data/pytd/pull/44>`__)
-  Disable ``type``, one of the Treasure Data-specific query parameters, because it is conflicted with the ``engine`` option.
   (`#45 <https://github.com/treasure-data/pytd/pull/45>`__)
-  Add `td-pyspark <https://pypi.org/project/td-pyspark/>`__ dependency for easily accessing to the `td-spark <https://support.treasuredata.com/hc/en-us/articles/360001487167-Apache-Spark-Driver-td-spark-FAQs>`__ functionalities.
   (`#46 <https://github.com/treasure-data/pytd/pull/46>`__, `#47 <https://github.com/treasure-data/pytd/pull/47>`__)

v0.7.0 (2019-08-23)
-------------------

-  Support ``if_exists="append"`` option in ``BulkImportWriter``.
   (`#38 <https://github.com/treasure-data/pytd/pull/38>`__)
-  ``PrestoQueryEngine`` and ``HiveQueryEngine`` accept Treasure
   Data-specific query parameters such as ``priority``.
   (`#41 <https://github.com/treasure-data/pytd/pull/41>`__)
