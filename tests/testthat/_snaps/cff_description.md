# Parse date

    cff-version: 1.2.0
    message: 'To cite package "rgeos" in publications use:'
    type: software
    license: GPL-2.0-or-later
    title: 'rgeos: Interface to Geometry Engine - Open Source (''GEOS'')'
    version: 0.5-7
    abstract: 'Interface to Geometry Engine - Open Source (''GEOS'') using the C ''API''
      for topology operations on geometries. Please note that ''rgeos'' will be retired
      by the end of 2023, plan transition to sf functions using ''GEOS'' at your earliest
      convenience. The ''GEOS'' library is external to the package, and, when installing
      the package from source, must be correctly installed first. Windows and Mac Intel
      OS X binaries are provided on ''CRAN''. (''rgeos'' >= 0.5-1): Up to and including
      ''GEOS'' 3.7.1, topological operations succeeded with some invalid geometries for
      which the same operations fail from and including ''GEOS'' 3.7.2. The ''checkValidity=''
      argument defaults and structure have been changed, from default FALSE to integer
      default ''0L'' for ''GEOS'' < 3.7.2 (no check), ''1L'' ''GEOS'' >= 3.7.2 (check
      and warn). A value of ''2L'' is also provided that may be used, assigned globally
      using ''set_RGEOS_CheckValidity(2L)'', or locally using the ''checkValidity=2L''
      argument, to attempt zero-width buffer repair if invalid geometries are found. The
      previous default (FALSE, now ''0L'') is fastest and used for ''GEOS'' < 3.7.2, but
      will not warn users of possible problems before the failure of topological operations
      that previously succeeded. From ''GEOS'' 3.8.0, repair of geometries may also be
      attempted using ''gMakeValid()'', which may, however, return a collection of geometries
      of different types.'
    authors:
    - family-names: Bivand
      given-names: Roger
      email: Roger.Bivand@nhh.no
      orcid: https://orcid.org/0000-0003-2392-6140
    - family-names: Rundel
      given-names: Colin
    preferred-citation:
      type: manual
      title: 'rgeos: Interface to Geometry Engine - Open Source (''GEOS'')'
      authors:
      - family-names: Bivand
        given-names: Roger
        email: Roger.Bivand@nhh.no
        orcid: https://orcid.org/0000-0003-2392-6140
      - family-names: Rundel
        given-names: Colin
      version: 0.5-7
      abstract: 'Interface to Geometry Engine - Open Source (''GEOS'') using the C ''API''
        for topology operations on geometries. Please note that ''rgeos'' will be retired
        by the end of 2023, plan transition to sf functions using ''GEOS'' at your earliest
        convenience. The ''GEOS'' library is external to the package, and, when installing
        the package from source, must be correctly installed first. Windows and Mac Intel
        OS X binaries are provided on ''CRAN''. (''rgeos'' >= 0.5-1): Up to and including
        ''GEOS'' 3.7.1, topological operations succeeded with some invalid geometries
        for which the same operations fail from and including ''GEOS'' 3.7.2. The ''checkValidity=''
        argument defaults and structure have been changed, from default FALSE to integer
        default ''0L'' for ''GEOS'' < 3.7.2 (no check), ''1L'' ''GEOS'' >= 3.7.2 (check
        and warn). A value of ''2L'' is also provided that may be used, assigned globally
        using ''set_RGEOS_CheckValidity(2L)'', or locally using the ''checkValidity=2L''
        argument, to attempt zero-width buffer repair if invalid geometries are found.
        The previous default (FALSE, now ''0L'') is fastest and used for ''GEOS'' < 3.7.2,
        but will not warn users of possible problems before the failure of topological
        operations that previously succeeded. From ''GEOS'' 3.8.0, repair of geometries
        may also be attempted using ''gMakeValid()'', which may, however, return a collection
        of geometries of different types.'
      repository-code: https://r-forge.r-project.org/projects/rgeos/
      url: https://trac.osgeo.org/geos/
      identifiers:
      - type: url
        value: http://rgeos.r-forge.r-project.org/index.html
      date-released: '2020-09-07'
      contact:
      - family-names: Bivand
        given-names: Roger
        email: Roger.Bivand@nhh.no
        orcid: https://orcid.org/0000-0003-2392-6140
      license: GPL-2.0-or-later
      year: '2020'
    repository-code: https://r-forge.r-project.org/projects/rgeos/
    url: https://trac.osgeo.org/geos/
    date-released: '2020-09-07'
    contact:
    - family-names: Bivand
      given-names: Roger
      email: Roger.Bivand@nhh.no
      orcid: https://orcid.org/0000-0003-2392-6140
    identifiers:
    - type: url
      value: http://rgeos.r-forge.r-project.org/index.html

# Parse date in another format

    cff-version: 1.2.0
    message: 'To cite package "basicdescdate" in publications use:'
    type: software
    license: GPL-3.0-only
    title: 'basicdescdate: A Basic Description with Date'
    version: 0.1.6
    abstract: A very basic description. Should parse without problems. I have a Date
    authors:
    - family-names: Basic
      given-names: Marc
      email: marcbasic@gmail.com
    preferred-citation:
      type: manual
      title: 'basicdescdate: A Basic Description with Date'
      authors:
      - family-names: Basic
        given-names: Marc
        email: marcbasic@gmail.com
      version: 0.1.6
      abstract: A very basic description. Should parse without problems. I have a Date
      repository-code: https://github.com/basic/package
      url: https://basic.github.io/package
      date-released: '1999-01-01'
      contact:
      - family-names: Basic
        given-names: Marc
        email: marcbasic@gmail.com
      license: GPL-3.0-only
      year: '1999'
    repository-code: https://github.com/basic/package
    url: https://basic.github.io/package
    date-released: '1999-01-01'
    contact:
    - family-names: Basic
      given-names: Marc
      email: marcbasic@gmail.com

# Parsing many urls

    cff-version: 1.2.0
    message: 'To cite package "manyurls" in publications use:'
    type: software
    license: GPL-3.0-only
    title: 'manyurls: A lot of urls'
    version: 0.1.6
    abstract: This package has many urls. Specifically, 1 Bug Reports and 6 URLs. Expected
      is to have 1 repository-code, 1 url and 3 URLs, since there is 1 duplicate and 1
      invalid url.
    authors:
    - family-names: Basic
      given-names: Marc
      email: marcbasic@gmail.com
    preferred-citation:
      type: manual
      title: 'manyurls: A lot of urls'
      authors:
      - family-names: Basic
        given-names: Marc
        email: marcbasic@gmail.com
      version: 0.1.6
      abstract: This package has many urls. Specifically, 1 Bug Reports and 6 URLs. Expected
        is to have 1 repository-code, 1 url and 3 URLs, since there is 1 duplicate and
        1 invalid url.
      repository-code: https://github.com/test/package
      url: https://test.github.io/package/
      identifiers:
      - type: url
        value: https://r-forge.r-project.org/projects/test/
      - type: url
        value: http://google.ru
      - type: url
        value: https://gitlab.com/r-packages/behaviorchange
      contact:
      - family-names: Basic
        given-names: Marc
        email: marcbasic@gmail.com
      license: GPL-3.0-only
      year: '2021'
    repository-code: https://github.com/test/package
    url: https://test.github.io/package/
    contact:
    - family-names: Basic
      given-names: Marc
      email: marcbasic@gmail.com
    identifiers:
    - type: url
      value: https://r-forge.r-project.org/projects/test/
    - type: url
      value: http://google.ru
    - type: url
      value: https://gitlab.com/r-packages/behaviorchange

# Parsing Gitlab

    cff-version: 1.2.0
    message: 'To cite package "codemetar" in publications use:'
    type: software
    license: GPL-3.0-only
    title: 'codemetar: Generate ''CodeMeta'' Metadata for R Packages'
    version: 0.1.6
    abstract: The 'Codemeta' Project defines a 'JSON-LD' format for describing software
      metadata, as detailed at <https://codemeta.github.io>. This package provides utilities
      to generate, parse, and modify 'codemeta.json' files automatically for R packages,
      as well as tools and examples for working with 'codemeta.json' 'JSON-LD' more generally.
    authors:
    - family-names: Boettiger
      given-names: Carl
      email: cboettig@gmail.com
      orcid: https://orcid.org/0000-0002-1642-628X
    - family-names: Salmon
      given-names: Maëlle
      orcid: https://orcid.org/0000-0002-2815-0399
    preferred-citation:
      type: manual
      title: 'codemetar: Generate ''CodeMeta'' Metadata for R Packages'
      authors:
      - family-names: Boettiger
        given-names: Carl
        email: cboettig@gmail.com
        orcid: https://orcid.org/0000-0002-1642-628X
      - family-names: Salmon
        given-names: Maëlle
        orcid: https://orcid.org/0000-0002-2815-0399
      version: 0.1.6
      abstract: The 'Codemeta' Project defines a 'JSON-LD' format for describing software
        metadata, as detailed at <https://codemeta.github.io>. This package provides utilities
        to generate, parse, and modify 'codemeta.json' files automatically for R packages,
        as well as tools and examples for working with 'codemeta.json' 'JSON-LD' more
        generally.
      repository-code: https://gitlab.com/ninijay/methoden
      url: https://ropensci.github.io/codemetar
      contact:
      - family-names: Boettiger
        given-names: Carl
        email: cboettig@gmail.com
        orcid: https://orcid.org/0000-0002-1642-628X
      keywords:
      - metadata
      - codemeta
      - ropensci
      - citation
      - credit
      - linked-data
      license: GPL-3.0-only
      year: '2021'
    repository-code: https://gitlab.com/ninijay/methoden
    url: https://ropensci.github.io/codemetar
    contact:
    - family-names: Boettiger
      given-names: Carl
      email: cboettig@gmail.com
      orcid: https://orcid.org/0000-0002-1642-628X
    keywords:
    - metadata
    - codemeta
    - ropensci
    - citation
    - credit
    - linked-data

# Parsing many persons

    cff-version: 1.2.0
    message: 'To cite package "manypersons" in publications use:'
    type: software
    license: GPL-3.0-only
    title: 'manypersons: A lot of persons'
    version: 0.1.6
    abstract: Overkill desc with many persons. Try this
    authors:
    - family-names: Hernangómez
      given-names: Diego
      email: fake@gmail.com
      orcid: https://orcid.org/0000-0001-8457-4658
    - family-names: Doe
      given-names: Joe
      affiliation: This One
      country: ES
    - family-names: Doe
      given-names: Pepe
      email: fake@gmail.com
    - name: I am an entity
      date-end: '2020-01-01'
    preferred-citation:
      type: manual
      title: 'manypersons: A lot of persons'
      authors:
      - family-names: Hernangómez
        given-names: Diego
        email: fake@gmail.com
        orcid: https://orcid.org/0000-0001-8457-4658
      - family-names: Doe
        given-names: Joe
        affiliation: This One
        country: ES
      - family-names: Doe
        given-names: Pepe
        email: fake@gmail.com
      - name: I am an entity
        date-end: '2020-01-01'
      version: 0.1.6
      abstract: Overkill desc with many persons. Try this
      repository-code: https://github.com/many/persons
      url: https://many.github.io/persons
      contact:
      - family-names: Hernangómez
        given-names: Diego
        email: fake@gmail.com
        orcid: https://orcid.org/0000-0001-8457-4658
      - name: I am an entity
        date-end: '2020-01-01'
      keywords:
      - metadata
      - cffr
      - ropensci
      - citation
      - credit
      - linked-data
      - one
      - two
      license: GPL-3.0-only
      year: '2021'
    repository-code: https://github.com/many/persons
    url: https://many.github.io/persons
    contact:
    - family-names: Hernangómez
      given-names: Diego
      email: fake@gmail.com
      orcid: https://orcid.org/0000-0001-8457-4658
    - name: I am an entity
      date-end: '2020-01-01'
    keywords:
    - metadata
    - cffr
    - ropensci
    - citation
    - credit
    - linked-data
    - one
    - two

# Parsing wrong urls

    cff-version: 1.2.0
    message: 'To cite package "wrongurls" in publications use:'
    type: software
    license: MIT
    title: 'wrongurls: Generate CodeMeta Metadata for R Packages'
    version: 0.1.0
    abstract: Codemeta defines a 'JSON-LD' format for describing software metadata. This
      package provides utilities to generate, parse, and modify codemeta.jsonld files
      automatically for R packages.
    authors:
    - family-names: Boettiger
      given-names: Carl
      email: cboettig@gmail.com
      orcid: https://orcid.org/0000-0002-1642-628X
    preferred-citation:
      type: manual
      title: 'wrongurls: Generate CodeMeta Metadata for R Packages'
      authors:
      - family-names: Boettiger
        given-names: Carl
        email: cboettig@gmail.com
        orcid: https://orcid.org/0000-0002-1642-628X
      version: 0.1.0
      abstract: Codemeta defines a 'JSON-LD' format for describing software metadata.
        This package provides utilities to generate, parse, and modify codemeta.jsonld
        files automatically for R packages.
      url: https://httpbin.org/status/404
      identifiers:
      - type: url
        value: https://httpbin.org/status/429
      - type: url
        value: https://www.github.es/ropensci/codemeta
      contact:
      - family-names: Boettiger
        given-names: Carl
        email: cboettig@gmail.com
        orcid: https://orcid.org/0000-0002-1642-628X
      keywords:
      - metadata
      - codemeta
      - ropensci
      - citation
      - credit
      - linked-data
      license: MIT
      year: '2021'
    url: https://httpbin.org/status/404
    contact:
    - family-names: Boettiger
      given-names: Carl
      email: cboettig@gmail.com
      orcid: https://orcid.org/0000-0002-1642-628X
    keywords:
    - metadata
    - codemeta
    - ropensci
    - citation
    - credit
    - linked-data
    identifiers:
    - type: url
      value: https://httpbin.org/status/429
    - type: url
      value: https://www.github.es/ropensci/codemeta

# Parsing two maintainers

    cff-version: 1.2.0
    message: 'To cite package "codemetar" in publications use:'
    type: software
    license: GPL-3.0-only
    title: 'codemetar: Generate ''CodeMeta'' Metadata for R Packages'
    version: 0.1.6
    abstract: The 'Codemeta' Project defines a 'JSON-LD' format for describing software
      metadata, as detailed at <https://codemeta.github.io>. This package provides utilities
      to generate, parse, and modify 'codemeta.json' files automatically for R packages,
      as well as tools and examples for working with 'codemeta.json' 'JSON-LD' more generally.
    authors:
    - family-names: Ok
      given-names: John
      email: email@email.edu
    - family-names: Doe
      given-names: Jane
      email: email2@email.edu
    - family-names: Doo
      given-names: Jane
    preferred-citation:
      type: manual
      title: 'codemetar: Generate ''CodeMeta'' Metadata for R Packages'
      authors:
      - family-names: Ok
        given-names: John
        email: email@email.edu
      - family-names: Doe
        given-names: Jane
        email: email2@email.edu
      - family-names: Doo
        given-names: Jane
      version: 0.1.6
      abstract: The 'Codemeta' Project defines a 'JSON-LD' format for describing software
        metadata, as detailed at <https://codemeta.github.io>. This package provides utilities
        to generate, parse, and modify 'codemeta.json' files automatically for R packages,
        as well as tools and examples for working with 'codemeta.json' 'JSON-LD' more
        generally.
      repository-code: https://github.com/ropensci/codemetar
      url: https://ropensci.github.io/codemetar
      contact:
      - family-names: Ok
        given-names: John
        email: email@email.edu
      - family-names: Doe
        given-names: Jane
        email: email2@email.edu
      license: GPL-3.0-only
      year: '2021'
    repository-code: https://github.com/ropensci/codemetar
    url: https://ropensci.github.io/codemetar
    contact:
    - family-names: Ok
      given-names: John
      email: email@email.edu
    - family-names: Doe
      given-names: Jane
      email: email2@email.edu

