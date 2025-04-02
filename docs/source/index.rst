.. _przykladowa-dokuemntacja:

============================
Przykładowa Dokumentacja
============================

Nagłówki tekstowe
=================

Nagłówek poziomu 2
------------------

Nagłówek poziomu 3
~~~~~~~~~~~~~~~~~~

Nagłówek poziomu 4
^^^^^^^^^^^^^^^^^^

Akapit tekstowy
===============

To jest przykładowy akapit zawierający treść dokumentacji.

Akapit informacyjny
===================

.. note::
   To jest przykład notatki (Note).

.. tip::
   To jest przykład wskazówki (Tip).

Fragment kodu
=============

Kod liniowy: ``print("Hello, World!")``

Kod blokowy:

.. code-block:: python

   def hello():
       print("Hello, World!")

Odnośniki
=========

Lokalny odnośnik do `innej sekcji <#naglowki-tekstowe>`_.

Zewnętrzny odnośnik do `Read the Docs <https://readthedocs.org>`_.

Listy
=====

Lista numerowana:

#. Pierwszy punkt
#. Drugi punkt
#. Trzeci punkt

Lista wypunktowana:

- Element pierwszy
- Element drugi
- Element trzeci

Lista definicji:

Termin 1
    Opis pierwszego terminu.
Termin 2
    Opis drugiego terminu.

Obraz
=====

.. image:: https://i.imgur.com/ZmFg8uL.jpeg
   :alt: Przykładowy obraz
   :align: center
   :figcaption: Opis obrazu

Tabela
======

.. list-table:: Przykładowa tabela
   :header-rows: 1

   * - Kolumna 1
     - Kolumna 2
   * - Wartość 1
     - Wartość 2
   * - Wartość 3
     - Wartość 4


.. toctree::

   usage
   api
