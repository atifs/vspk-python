.. _nuptranslationmap:

nuptranslationmap
===========================================

.. class:: nuptranslationmap.NUPTranslationMap(bambou.nurest_object.NUMetaRESTObject,):

1:1 mappings of private IPs in provider domain to the provider  alias (public) IPs in customer domain and N:1 mappings of a collection of provider private IPs to a provider alias IP into the customer domain.


Attributes
----------


- ``spat_source_list``: The list of provider source IPs to be SPAT'd.

- ``mapping_type`` (**Mandatory**): 1:1 NATmapping, or *:1 PAT mappings

- ``provider_alias_ip`` (**Mandatory**): Provider public IP in Customer Domain

- ``provider_ip`` (**Mandatory**): Provider private IP in Provider Domain.






Parents
--------


- :ref:`nupsnatpool.NUPSNATPool<nupsnatpool>`

