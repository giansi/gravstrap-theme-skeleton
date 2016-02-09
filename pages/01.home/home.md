---
title: Home
metadata:
  description: Gravstrap Theme helps you to start a new Grav CMS site with Bootstrap support and several ready to use modules. It is also perfect to extend to start a new Bootstrap custom theme, to fit your needs.
slug: welcome-to-gravstrap-theme

content:
    items: @self.modular
    order:
        by: default
        dir: asc
        custom:
            - _showcase
            - _what_we_do
            - _portfolio
            - _clients
            - _team
            - _where_we_are
            - _contacts

simple_form:
        token: "xxxxx"
        template_file: default
        redirect_to: /thank-you-for-my-page

googlemaps:
    map:
        center: 41.90278, 12.49637
        zoom: 12
        #type: TERRAIN
        markers:
            - location: 41.90278, 12.49637
              title: Gravstrap Theme
              zIndex: 1
              timeout: 1000
              info: <strong>Meet Us</strong>.<br/>We are there!
---

[bootstrap-jumbotron id="jumbotron1" fullwidth="true" image="bg.jpg" render=false]
# Gravstrap theme

Gravstrap Theme helps you to start a new Grav CMS site with Bootstrap support and several ready to use modules. It is also perfect to start a new Bootstrap custom theme, to create your unique design.

[/bootstrap-jumbotron]


[what-we-do id="what_we_do" attributes="class:what-we-do module" column_attributes="class:col-md-12"]

## Explain your business
Use the `What we do module` to explain your customers the services you offer.
___

[what-we-do-item attributes="class:col-md-4"]

[icon icon="bullhorn fa-5x" icon_type="fontawesome"][/icon]
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

[/what-we-do-item]

[what-we-do-item attributes="class:col-md-4"]

[icon icon="bolt fa-5x" icon_type="fontawesome"][/icon]
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

[/what-we-do-item]

[what-we-do-item attributes="class:col-md-4"]

[icon icon="heart fa-5x" icon_type="fontawesome"][/icon]
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
[/what-we-do-item]

[/what-we-do]


[portfolio id=portfolio attributes="class:portfolio module"]

## Showcase your work
Use the `Portfolio module` to spread your works to the world

___

[bootstrap-thumbnail]
[bootstrap-thumbnail-item image="coffee.jpg" url="http://diblas.net"][/bootstrap-thumbnail-item]
[bootstrap-thumbnail-item image="farmerboy.jpg" url="http://diblas.net"][/bootstrap-thumbnail-item]
[bootstrap-thumbnail-item image="girl.jpg" url="http://diblas.net"][/bootstrap-thumbnail-item]
[bootstrap-thumbnail-item image="judah.jpg" url="http://diblas.net"][/bootstrap-thumbnail-item]
[bootstrap-thumbnail-item image="origami.jpg" url="http://diblas.net"][/bootstrap-thumbnail-item]
[bootstrap-thumbnail-item image="retrocam.jpg" url="http://diblas.net"][/bootstrap-thumbnail-item]
[/bootstrap-thumbnail]

[/portfolio]


[clients id=clients attributes="class:clients module"]

## Show out the clients who trust your business
Use the `Clients module` to show your customers, the clients who already trust your business

___

[clients-item image="apple.svg" attributes="class:col-md-3"][/clients-item]
[clients-item image="canon.svg" attributes="class:col-md-3"][/clients-item]
[clients-item image="forbes.svg" attributes="class:col-md-3"][/clients-item]
[clients-item image="hp.svg" attributes="class:col-md-3"][/clients-item]
[clients-item image="intel.svg" attributes="class:col-md-3"][/clients-item]
[clients-item image="samsung.svg" attributes="class:col-md-3"][/clients-item]
[clients-item image="siemens.svg" attributes="class:col-md-3"][/clients-item]
[clients-item image="vaio.svg" attributes="class:col-md-3"][/clients-item]

[/clients]

[team id=team attributes="class:team module"]

## Introduce your awesome team
Use the `Team module` to introduce your awesome team.

___

[team-item image="jane.jpg" attributes="class:col-md-4"]
[link url="#" icon="twitter" icon_type="fontawesome" stacked=true][/link]
[link url="#" icon="facebook" icon_type="fontawesome" stacked=true][/link]
[link url="#" icon="linkedin" icon_type="fontawesome" stacked=true][/link]
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
[/team-item]
[team-item image="mark.jpg" attributes="class:col-md-4"]
[link url="#" icon="twitter" icon_type="fontawesome" stacked=true][/link]
[link url="#" icon="facebook" icon_type="fontawesome" stacked=true][/link]
[link url="#" icon="linkedin" icon_type="fontawesome" stacked=true][/link]
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
[/team-item]
[team-item image="julia.jpg" attributes="class:col-md-4"]
[link url="#" icon="twitter" icon_type="fontawesome" stacked=true][/link]
[link url="#" icon="facebook" icon_type="fontawesome" stacked=true][/link]
[link url="#" icon="linkedin" icon_type="fontawesome" stacked=true][/link]
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
[/team-item]
[/team]

[where-we-are id=where-we-are attributes="class:module where-we-are"]

## Show your customers where you are
Use the `Where we are` module to tell your customers where you are

___

[GOOGLEMAPS:map]

[/where-we-are]

[contacts id=contacts attributes="class:module contacts" info_attributes="class:col-md-4" form_attributes="class:col-md-8"]

## Let your customers contact you
Use the Contact module to let your customers contact you

___

[section name="form"]
##### Get in touch
Need some information? Ask us a question filling the form below

[simple-form token="xxxxx" redirect_to="/thank-you-for-my-page" render=true][/simple-form]
[/section]

[section name="info"]
#####OFFICE

9 - 3815 Thatcher Avenue  
Saskatoon, Saskatchewan  
S7R 1A3

#####CONTACT INFORMATION

**Primary Phone:** 1 (555) 555 - 6666  
**Alternate Phone:** 1 (555) 555 - 7777  
**Fax:** 1 (555) 555 - 8888


#####OFFICE HOURS

Monday - Friday 8 am - 5 pm  
Saturday - Sunday Closed  
[/section]
[/contacts]
