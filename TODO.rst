TODO
====

Please translate to English:

Een V achter de taak geeft aan dat het af is.
Een 1/2 achter de taak betekent dat ik halverwege ben

Taken staan niet indented
Comments over taken staan wel indented


Tasks
------
1.  Naar nieuwe git repo **done**
2.  Date issue
3.  org issue -> kijkt mathijs nog naar
4.  geïnternationaliseerde (zie Django docs) verbose_name geeft
5.  django-extensions graph_models **done**
6.  admin interface
7.  inline admin for manytomany
8.  view in admin voor uploaden vcard
9.  AGPL
10. Finish setup
    opzet file, moet nog testen, admin houd ik ook nog geen rekening mee
11. README.rst (reStructuredText) **done**
12. convertTo  **done**
    gedaan als importFrom and exportTo
13. gitignore **done**
14. pep8 **done**
    gebruikte commando om whitespace om id's toe te staan;
    `pep8 -r --count --ignore=E201,E202,E221,E251 django_vcard.py`
15. Remove application files in root directory (`manage.py`, `urls.py`, `templates`, `*.pyc`, etc.) **done**
16. Unittests from `vcard/models.py` to `vcard/tests/__init__.py`
17. Sensible data types for (at least):
    
    * URL (URLField)
    * Timezone (int, I believe - see what vobject returns)
    * Photo, Sound, Logo (blob/binary field?)
    * Note (TextField)
    * Address, email and tel type (ChoiceField)
    * Geo (maybe Lat/lon. - otherwise leave as a string)
    * Email (EmailField)
    * Bday (DateField)
    * Rev (Integer, maybe?)
18. Docstrings for at least all the models, and some of the main functions.
    From the docstring the following things should roughly be clear:
    
    1. What does the function do (semantically, not algorithmically)
       
       Something like: "It eats bananas." 
       
       NOT: "It uses enzymes do digest such and such carbonhydrates etc. etc."
    2. What does it return (if it returns anything at all).
    3. What the meaning of eventual parameters are, especially if they're not
       downright evident.

