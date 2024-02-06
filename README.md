# Syrup
A little sugar for your searches. Rust TUI to run a structured search across multiple domains in parallel, conveniently browse collections of query results from each domain.

The simple, minimal query-builder provided by the TUI handles the same search engine syntax keywords and operators consistent with conventional search engine specifiers in the browser (Google, DuckDuckGo, Brave, Yandex, etc.) PLUS additional shell-like custom search query syntax, such as listing domains `{domain1,domain2,...}` which allows us to specify a more detailed scope than these browser tools would in a single search.

The goal of this tool is to provide greater control to narrow or broaden the scope of searches that would normally need to be repetitively done in multiple tabs to find results matching on a number of phrases, keywords, logical operations, or domains/subdomains.

Future road-map ideas for the project include:
- persisting the collections of result data from previous queries into a history db
- providing a built-in way to quickly access and browse collections in the TUI, with features to modify, select, organize, and rerun these search items
- tab-completion for commonly used specifiers such as a user list of favorite domains found in a config file
- simple syntax highlighting and optional cheatsheet display to help validate search errors
