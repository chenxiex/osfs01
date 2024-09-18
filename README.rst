Operating System From Scratch
-----------------------------

Step 01: A smallest "OS"
````````````````````````

Let's begin with a simplest boot sector. You'll see how easy it is to get started!

Here we go:

+ Install nasm_ the assembly compiler and qemu_ the emulator. I highly recommend using the package manager of your distribution to install them.

+ Clone me (we're in GitHub, aren't we)::

      $ git clone https://github.com/chenxiex/osfs01.git

+ Run your smallest "OS" right now::

      $ cd osfs01
      $ make

  Guess what? It's running!

  The screen is a little messy but you can see the red "Hello, OS world!", which means our boot sector works!

`‹prev`_   `next›`_

.. _nasm: http://nasm.us/
.. _qemu: https://www.qemu.org/
.. _`‹prev`: https://github.com/chenxiex/osfs00
.. _`next›`: https://github.com/chenxiex/osfs02
