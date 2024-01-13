API
===

Work with pipes
---

Create pipe
.. code-block:: http

POST http://<domain>/pipe
Content-Type: application/json

{
   "name": "Pipe name",
   "namespace": "path.to.pipe",
   "settings": {
      "active": true,
      "debug": false
   }
}


.. autosummary::
   :toctree: generated

   lumache
