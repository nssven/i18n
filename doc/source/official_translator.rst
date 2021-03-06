=============================
Official OpenStack translator
=============================

Steps to become a OpenStack translator
======================================

Translation is another kind of important contribution to OpenStack
community. If you want to become a official translator, you need to
finish following steps:

1. Before you start contribution, you'll have to `agree
   to the contributor license agreement
   <http://docs.openstack.org/infra/manual/developers.html#account-setup>`_.
   (You can preview the full text of `the OpenStack Individual
   Contributor License Agreement
   <https://review.openstack.org/static/cla.html>`_ first if you want.)

   .. note::

      If you want to become a translator only, simply speaking,
      you need to `join The OpenStack Foundation
      <https://www.openstack.org/join/>`_
      (select "Foundation Member") and
      `sign the appropriate Individual Contributor License Agreement
      <http://docs.openstack.org/infra/manual/developers.html#sign-the-appropriate-individual-contributor-license-agreement>`_.

2. Register a user ID in Zanata

   * Go to `Zanata server <https://translate.openstack.org/>`_
   * Click "Log in" button.
   * If you don't have OpenStack ID,
     `register one <https://www.openstack.org/join/register>`_.
   * After you log in with OpenStack ID, you will be requested to fill in
     your profile.

   .. note::

      You are encouraged to register with your business email,
      which will help your company to get the credit. If you don't
      want to, use your personal email will be OK too.

3. Request to join a translation team

   * Click "Languages" on the top, all languages will be listed.
   * Click the language you want to translate, the language page will
     be shown.
   * Click "..." on the right, and select "Request to join team".
   * Input a short introduction of yourself, including your name, as
     "Additional information", then click "Send message".

   .. note::

      Make sure to include a short introduction because it is the
      only information which language coordinators can use to
      determine your join request is valid or not.

4. When your request is approved, you will get an email notification.

5. Now you can start your translation.
   You can actually become an OpenStack official translator
   by contributing translations.
   You can find :doc:`various ways of contributions <contributing>`.

ATC status in i18n project
==========================

The i18n project is an official OpenStack project, so official translators
who have contributed in a specific period are regarded as
"ATC" (Active Technical Contributor) and
"APC" (Active Project Contributor) of the i18n project.
APC can vote for the i18n PTL (Project Team Lead).
For more detail about what ATC and APC,
see `OpenStack Technical Committee Charter <http://governance.openstack.org/reference/charter.html>`__.

As of now, ATC of official translators are treated as extra ATCs
as we have no way to collect statistics automatically now.
The list of extra ATCs is maintained by the PTL and is usually updated
short before the deadline of extra ATCs nomination in each release cycle.
The deadline of extra ATCs nomination can be checked in the release
schedule page at http://releases.openstack.org/ (for example,
http://releases.openstack.org/newton/schedule.html).

Currently translators who translate 300 words in the last six months
until the deadline of extra ATCs nomination are nominated as ATCs,
and the ATC status of translators is valid for one year.
The detail period is determined by the PTL in each cycle.
For Newton cycle, the six month period was from 2016-02-01 to 2016-07-31,
and this ATC status will expire on July 2017 if there will be no
additional translation contributions.
If you have a question, feel free to ask it to the PTL or the i18n list.

Note that contributors to openstack/i18n repository are acknowledged
as ATC automatically in the same way as for most OpenStack projects.
