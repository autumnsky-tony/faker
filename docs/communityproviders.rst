.. ref-communityproviders:

Community Providers
===================

Here's a list of Providers written by the community:

+---------------+--------------------------+----------------------------------+
| Provider name | Description              | URL                              |
+===============+==========================+==================================+
| Credit Score  | Fake credit score data   | `faker_credit_score`_            |
|               | for testing purposes     |                                  |
+---------------+--------------------------+----------------------------------+
| Microservice  | Fake microservice names  | `faker_microservice`_            |
+---------------+--------------------------+----------------------------------+
| Posts         | Fake posts in markdown   | `mdgen`_                         |
|               | format                   |                                  |
+---------------+--------------------------+----------------------------------+
| Vehicle       | Fake vehicle information | `faker_vehicle`_                 |
|               | includes Year Make Model |                                  |
+---------------+--------------------------+----------------------------------+
| WebProvider   | Web-related data such as | `faker_web`_                     +
|               | mime-type and web server |                                  +
|               | versions.                |                                  +
+---------------+--------------------------+----------------------------------+
| Wi-Fi ESSID   | Fake Wi-Fi ESSIDs.       | `faker_wifi_essid`_              +
+---------------+--------------------------+----------------------------------+
| Airtravel     | Airport names, airport   | `faker_airtravel`_               |
|               | codes, and flights.      |                                  |
+---------------+--------------------------+----------------------------------+

If you want to add your own provider to this list, please submit a Pull Request to our `repo`_.

In order to be inlcuded, your provider must satisfy these requirement:

* it must have tests.
* it must be published on PyPI.
* it must have an `OSI-Approved`_ License.
* it must not duplicate any functionality already present in ``Faker``.
* it must not contain any profanity, either in code or in documentation.
* it must not contain any malicious nor any kind of telemetry code.

.. _repo: https://github.com/joke2k/faker/
.. _OSI-Approved: https://opensource.org/licenses/alphabetical
.. _faker_web: https://pypi.org/project/faker_web/
.. _faker_wifi_essid: https://pypi.org/project/faker-wifi-essid/
.. _faker_credit_score: https://pypi.org/project/faker-credit-score/
.. _faker_microservice: https://pypi.org/project/faker-microservice/
.. _faker_vehicle: https://pypi.org/project/faker-vehicle/
.. _mdgen: https://pypi.org/project/mdgen/
.. _faker_airtravel: https://pypi.org/project/faker_airtravel/
