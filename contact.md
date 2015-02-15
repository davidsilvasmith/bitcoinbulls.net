---
layout: sidebar-container
title: Contact
subtitle: Get in Touch 
includeJoin: 1
permalink: /contact/
---
{% assign companyContact = site.data.people[site.data.information.companyContact] %}

# Get in Touch!

Lets talk! Seriously!

I love bitcoin and am happy to talk with you. Feel free to reach me at any of the methods below:

<div itemscope itemtype="http://schema.org/Organization"> 
   <span itemprop="name">{{site.data.information.title}}</span> 
   Located at 
   <div itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
      {%if companyContact.telephone %} <span itemprop="streetAddress">{{ companyContact.streetAddress}}</span>, {% endif %}
      {%if companyContact.addressLocality %} <span itemprop="addressLocality">{{ companyContact.addressLocality}}</span>, {% endif %}
      {%if companyContact.addressRegion %} <span itemprop="addressRegion">{{ companyContact.addressRegion}}</span> {% endif %}
      {%if companyContact.postalCode %} <span itemprop="postalCode">{{ companyContact.postalCode}}</span> {% endif %}
      {%if companyContact.addressCountry %} <span itemprop="addressCountry">{{ companyContact.addressCountry}}</span> {% endif %}
   </div>
   {%if companyContact.telephone %} Tel:<span itemprop="telephone">{{ companyContact.telephone}} </span>, {% endif %}
   {%if companyContact.faxNumber %} Fax:<span itemprop="faxNumber">{{ companyContact.faxNumber}}</span>, {% endif %}
   {%if companyContact.email %} E-mail: <a href="mailto:{{companyContact.email}}"><span itemprop="email">{{ companyContact.email}}</span></a> {% endif %}
  {%if site.data.information.logo %} <img itemprop="logo" src="{{site.data.information.logo }}" /> {% endif %}
   {%if companyContact.telephone %} Phone: <span itemprop="telephone">{{ companyContact.telephone}}</span> {% endif %}
   {%if site.data.information.url %} <a href="{{site.data.information.url}}" itemprop="url">{{site.data.information.url}}</a> {% endif %}
</div>

<hr />