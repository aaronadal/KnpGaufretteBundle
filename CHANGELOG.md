v0.6.0
======

In #204 :

- Require PHP 7.1 as minimum (previous php versions are EOL)
- PHP 7.3 support
- Update Gaufrette dep to v0.8
- Update Symfony deps to v4

v0.5.3
======

- Fix composer.json validity #184
- Be able to install Gaufrette v0.6 #185

v0.5.2
======

- Declare command as service to fix sf3.4 deprecation #183<Paste>

v0.5.1
======

- Be able to install Gaufrette 0.5 [#178]

v0.5.0
======

* Add `utf8` parameter to FTP adapter config
* Add some docs about S3 regions
* Fix config example for S3 adapter (#153)
* Add `multi_container_mode` to Azure adapter config (#158)
* Add missing documentation about `detect_content_type` for S3 adapter (#161)
* Fix configuration processing (#163)
* Fix deprecation warnings with Symfony >= 3.3 (#165)
* Add docs about metapackages (#168)
* Fix doc link (#169)
* Adding Symfony 4 support (#171)
* Use PHPUnit\Framework\TestCase instead of PHPUnit_Framework_TestCase (#172)
* Bump Gaufrette version (#173)
* Add use cases documentation (#175)
* Declare filesystem services as public (#176)
* Drop support for old PHP versions 5.3, 5.4, 5.5 (#177)

Thanks to: @000panther, @NiR-, @jspizziri, @kesslerdev, @vyacheslavk, @Lctrs, @nicolasmure, @silvioq, @bocharsky-bw, @carusogabriel, @7thcubic, @aguidis, @bluntelk, @rjd22.
