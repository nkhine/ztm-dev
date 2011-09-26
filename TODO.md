* Site structure - This should should also include for example technology specific projects such as Energy, Transportation, Water, Food; this way there is a structure for best practices of what, individuals and communities can do and what technologies are available at the present time to fulfill these basic needs.
As an example, each district within a town should work in setting up an Aquaponics facility to provide fruits, vegetables and flowers within that district.
All the fruits, vegetables and flowers produced by the district aquaponics facility will be supplied to the schools within this district. This way each child at the school will have pesticide free fruits and vegetables and at the same time we are etching away the foundations of the monetary system.
We need to have a wiki to outline the steps required to get this done with a cost benefit analysis (we are still living in a monetary system) this document will need to be simple with graphics detailing how this will work and the benefits to the community as a whole.
The steps that need to be taken to implement this, feedback procedure, etc...

* "Migrate":http://wiki.github.com/mojombo/jekyll/blog-migrations from previous system.

* l10n - localization of the project sites.
  It is important to have a consistent look & feel for each 'Chapter', whether this is International, Regional or even Town specific. It is thus encouraged to 'clone' the site and use this as your template for your local 'Chapter' this way any updates on the 'master' branch can be merged into your specific 'Chapter' code. And allows us to have a 'one' version through out the entire community.
  
  Discuss best l10n practices... is it better to have http://tld.zeitgeist.x11.us where the 'tld' is the country specific iana_root_zone, this way the URI schema can be, for example for France:
  
    ├── http://zeitgeist.x11.us (root site)
    │   ├── http://fr.zeitgeist.x11.us (French Chapter) * Country
    │   │   ├── http://languedoc-roussillon.fr.zeitgeist.x11.us (Languedoc-Roussillon Chapter) * Region
    │   │   │   └── http://gard.languedoc-roussillon.fr.zeitgeist.x11.us (Gard Chapter) * County
    │   │   │   │   └── http://nimes.gard.languedoc-roussillon.fr.zeitgeist.x11.us (Nîmes Chapter) * Town

* i18n - internationalization of the content such as howtos, blog posts, wikis, images, videos etc...

