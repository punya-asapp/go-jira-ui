Changelog
=========

v0.4.0
------

* #3: Implement 'NextTicket' and 'PrevTicket'
* Add :create {project} {summary} command
* #31 - use age template function
* #8 - Allow breaking out of the UI to run external commands (eg vim)
* Add various quick search commands
* Add 'previousPages history', to make 'q' less painful
* Swtich to use ScrollableList base interface widget

v0.3.2
------

* Bugfix: allow 2-character project names for findTicketIdInString [Aneesh Goel]

v0.3.1
------

* Bugfix: incorrect logging level causing display error

v0.3.0
------

* Search history and Command History work across all pages

v0.2.0
------

* Add :view TICKET command
* Add :query JQL commands

v0.1.1
------

* Fix bug: refresh can make cachedResults shorter, causing slice index panic

v0.1.0
------

* Initial release
