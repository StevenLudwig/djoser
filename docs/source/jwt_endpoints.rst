JWT Endpoints
=============

JWT Create
----------

Use this endpoint to obtain JWT.

**Default URL**: ``/jwt-token/create/``

+----------+---------------------------------+----------------------------------+
| Method   |           Request               |           Response               |
+==========+=================================+==================================+
| ``POST`` | * ``token``                     | ``HTTP_200_OK``                  |
|          |                                 |                                  |
|          |                                 | * ``token``                      |
|          |                                 |                                  |
|          |                                 | ``HTTP_400_BAD_REQUEST``         |
|          |                                 |                                  |
|          |                                 |  * ``non_field_errors``          |
+----------+---------------------------------+----------------------------------+

JWT Refresh
-----------

Use this endpoint to refresh JWT.

**Default URL**: ``/jwt-token/refresh/``

+----------+---------------------------------+----------------------------------+
| Method   |           Request               |           Response               |
+==========+=================================+==================================+
| ``POST`` | * ``token``                     | ``HTTP_200_OK``                  |
|          |                                 |                                  |
|          |                                 | * ``token``                      |
|          |                                 |                                  |
|          |                                 | ``HTTP_400_BAD_REQUEST``         |
|          |                                 |                                  |
|          |                                 |  * ``non_field_errors``          |
+----------+---------------------------------+----------------------------------+

JWT Verify
----------

Use this endpoint to verify JWT.

**Default URL**: ``/jwt-token/verify/``

+----------+---------------------------------+----------------------------------+
| Method   |           Request               |           Response               |
+==========+=================================+==================================+
| ``POST`` | * ``token``                     | ``HTTP_200_OK``                  |
|          |                                 |                                  |
|          |                                 | * ``token``                      |
|          |                                 |                                  |
|          |                                 | ``HTTP_400_BAD_REQUEST``         |
|          |                                 |                                  |
|          |                                 |  * ``non_field_errors``          |
+----------+---------------------------------+----------------------------------+
