# MeshCompare

A selection of tools to visualize differences between mesh objects.
These are visualized as vertex colors.

Currently there is only a python script that does a comparison on a single frame, but I will eventually add a deformer
node that will do the same dynamically.


# Usage

## Python Script

1. Copy the `meshCompare.py` to your Maya scripts folder or anywhere in its `PYTHONPATH`
2. Now you can run the following python

    ```python
    from meshCompare import static_compare
    static_compare('pCube2', 'pCube1')
    ```