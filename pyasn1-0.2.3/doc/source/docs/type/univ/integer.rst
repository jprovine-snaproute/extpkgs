
.. |ASN.1| replace:: Integer

|ASN.1| type
------------

.. autoclass:: pyasn1.type.univ.Integer(value=NoValue(), tagSet=TagSet(), subtypeSpec=ConstraintsIntersection(), namedValues=NamedValues())
   :members: hasValue, isSameTypeWith, isSuperTypeOf, tagSet, subtypeSpec, namedValues

   .. note::

        The |ASN.1| type models an arbitrary integer. INTEGER values can be positive, negative,
        or zero, and can have any magnitude.
       
   .. automethod:: pyasn1.type.univ.Integer.clone(value=NoValue(), tagSet=TagSet(), subtypeSpec=ConstraintsIntersection(), namedValues=NamedValues())
   .. automethod:: pyasn1.type.univ.Integer.subtype(value=NoValue(), implicitTag=Tag(), explicitTag=Tag(),subtypeSpec=ConstraintsIntersection(), namedValues=NamedValues())
