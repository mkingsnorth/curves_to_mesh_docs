#####################################
Tips and Troubleshooting
#####################################

.. note::
    
    If you are having any issues do not hesitate to :ref:`Contact Us <contact>`


.. _create_patches:

----------------------------------------------------------------------------------
Creating Curve Surfaces
----------------------------------------------------------------------------------

In the default "Surface to Mesh" mode, the add-on uses curves to create mesh surfaces.  The curves will be in interlocking 'patches', as described below.

To create 4 interlocking curves:


#. Ensure that the Snap during Transform magnet icon is selected and that the Snap Element type is set to Vertex. This will ensure you can create a curve that can snap to another curve's corners:

    .. image:: _static/images/snap_to_vertex.png
        :alt: Snap to Vertex
        :width: 600px

    .. image:: _static/images/snap_to_vertex2.png
        :alt: Snap to Vertex
        :width: 600px

#. Create 4 curves and arrange them in a 2x2 layout:

    .. image:: _static/images/patches.png
        :alt: Patches
        :width: 600px

#. Note that you can add as many control points as you like to make complex layouts:

    .. image:: _static/images/c2m_patches_layout.gif
        :alt: Patches 2
        :width: 600px

#. You an also create a network of interlocking 3 sided curves to create more complex surfaces:    

    .. image:: _static/images/c2m_patch_network.gif
        :alt: Patches 3
        :width: 600px

.. tip::

    You can split the shapes into 4 by selecting the vertices to separate and pressing 'p':

    .. image:: _static/images/split_patches.gif
        :alt: Split Patches
        :width: 600px
    





----------------------------------------------------------------------------------
Extra Curve Objects
----------------------------------------------------------------------------------

I recommend you install `Add Curve: Extra Objects <https://extensions.blender.org/add-ons/extra-curve-objectes/>`_, freely available with the standard Blender installation.  This will give you a lot more shapes to play with out of the box:
