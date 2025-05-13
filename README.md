# Data-Diccionary
Data dictionary implemented in C language   Hugo Alba Medina

This program manages a binary data dictionary, where:

Each Entity can have several associated Attributes.
It is saved in a binary file (DiccionarioBinario.bin).\n
Each entity and attribute are linked to the next one via addresses (offsets) in the file, like a linked list on disk.