tripy
-----

Tripy is a simple module with one purpose: triangulating polygons.


Getting Started
---------------

.. code:: bash

    pip install tripy

.. code:: python
    import tripy
    # Polygon can be clockwise or counter-clockwise
    polygon = [(0,1), (-1, 0), (0, -1), (1, 0)]
    triangles = tripy.earclip(polygon)
    print triangles
    #[((1, 0), (0, 1), (-1, 0)), ((1, 0), (-1, 0), (0, -1))]


Roadmap
-------
0.1
- Support polygons with holes
0.2
- Implement `Seidel's triangulation <http://gamma.cs.unc.edu/SEIDEL/>`__