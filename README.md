# Perl Toolbox

A curated list of Perl libraries by category. For an alternative list check out [Task::Kensho](https://metacpan.org/pod/Task::Kensho).

## General Libraries

- Character encodings - [Encode](https://metacpan.org/pod/Encode)
- Data structure printer - [Data::Dumper](https://metacpan.org/pod/Data::Dumper)
- Date/Time - [DateTime](https://metacpan.org/pod/DateTime), [Time::Moment](https://metacpan.org/pod/Time::Moment), [Time::Piece](https://metacpan.org/pod/Time::Piece)
- Date/Time, parser - [Time::ParseDate](https://metacpan.org/pod/Time::ParseDate)
- Email sending - [Email::Stuffer](https://metacpan.org/pod/Email::Stuffer) [Email::Sender](https://metacpan.org/pod/Email::Sender)
- Fake data generator - [Data::Fake](https://metacpan.org/pod/Data::Fake)
- File paths - [Path::Tiny](https://metacpan.org/pod/Path::Tiny)
- JSON schema validator - [JSON::Validator](https://metacpan.org/pod/JSON::Validator)
- Logging (Log4j) - [Log::Log4perl](https://metacpan.org/pod/Log::Log4perl)
- Task automation - [Rex](https://metacpan.org/pod/Rex)
- Templates - [Mojo::Template](https://docs.mojolicious.org/Mojo/Template), [Template::Toolkit](https://metacpan.org/pod/Template::Toolkit)
- Text wrapping and reformatting [Text::Autoformat](https://metacpan.org/pod/Text::Autoformat)

## Terminal
- ANSI colors - [Term::ANSIColor](https://metacpan.org/pod/Term::ANSIColor)
- Command-line apps (CLI) - [App::Cmd](https://metacpan.org/pod/App::Cmd)

## Concurrency

- Async/Event loop - [POE](https://metacpan.org/pod/POE), [IO::Async](https://metacpan.org/pod/IO::Async) [Mojo::IOLoop](https://metacpan.org/pod/Mojo::IOLoop)
- Job queue - [Minion](https://metacpan.org/pod/Minion)
- Parallel process forking - [Parallel::ForkManager](https://metacpan.org/pod/Parallel::ForkManager)
- Worker pools - [MCE](https://metacpan.org/pod/MCE)

## Database

- Database driver interface - [DBI](https://metacpan.org/pod/DBI)
- Elasticsearch client - [Search::Elasticsearch](https://metacpan.org/pod/Search::Elasticsearch)
- Migrations - [sqitch](https://metacpan.org/dist/App-Sqitch/view/lib/sqitch.pod)
- ORM - [DBIx::Class](https://metacpan.org/pod/DBIx::Class)
- PostgreSQL driver + migrations - [Mojo::Pg](https://metacpan.org/pod/Mojo::Pg)
- SQLite driver + migrations - [Mojo::SQLite](https://metacpan.org/pod/Mojo::SQLite)
- SQLite server - [DBD::SQLite](https://metacpan.org/pod/DBD::SQLite)
- Test framework - [Test2::Suite](https://metacpan.org/pod/Test2::Suite)

## File Formats

- Config file loader, multi-format - [Config::Any](https://metacpan.org/pod/Config::Any)
- Config files, Apache format - [Config::General](https://metacpan.org/pod/Config::General)
- JSON - [JSON::MaybeXS](https://metacpan.org/pod/JSON::MaybeXS)
- PDF writer - [PDF::API2](https://metacpan.org/pod/PDF::API2)
- TAR archives - [Archive::Tar](https://metacpan.org/pod/Archive::Tar)

## Images

- Exif metadata - [Image::ExifTool](https://metacpan.org/pod/Image::ExifTool)

## Math

- Cryptography - [CryptX](https://metacpan.org/pod/CryptX)
- N-dimensional arrays - [PDL](https://metacpan.org/dist/PDL/view/Basic/Pod/API.pod)

## Cloud

- AWS - [Paws](https://metacpan.org/pod/Paws)

## Web Programming

- Browser automation (Chrome) - [WWW::Mechanize::Chrome](https://metacpan.org/pod/WWW::Mechanize::Chrome)
- Browser automation (Selenium) - [WWW::Selenium](https://metacpan.org/pod/WWW::Selenium)
- DNS resolver - [Net::DNS](https://metacpan.org/release/NLNETLABS/Net-DNS-1.32/view/lib/Net/DNS.pm)
- DOM parser - [Mojo::DOM](https://metacpan.org/pod/Mojo::DOM)
- GraphQL - [GraphQL](https://metacpan.org/pod/GraphQL)
- HTTP/1.1 client - [HTTP::Tiny](https://metacpan.org/pod/HTTP::Tiny)
- File MIME type detection - [File::LibMagic](https://metacpan.org/pod/File::LibMagic)
- Minify CSS - [CSS::Packer](https://metacpan.org/pod/CSS::Packer)
- Minify HTML - [HTML::Packer](https://metacpan.org/pod/HTML::Packer)
- Minify JavaScript - [JavaScript::Packer](https://metacpan.org/pod/JavaScript::Packer)
- User agent detector - [HTTP::BrowserDetect](https://metacpan.org/pod/HTTP::BrowserDetect)
- Web app framework, interface (PSGI) - [Plack](https://metacpan.org/pod/Plack)
- Web app framework, lightweight - [Dancer](https://metacpan.org/pod/Dancer)
- Web app framework, MVC - [Catalyst](https://metacpan.org/pod/Catalyst)
- Web app framework, real-time [Mojolicious](https://metacpan.org/pod/Mojolicious)
- Web scraper - [Mojo::UserAgent](https://docs.mojolicious.org/Mojo/UserAgent), [WWW::Mechanize](https://metacpan.org/pod/WWW::Mechanize)
- Web server - [Starman](https://metacpan.org/pod/Starman)

## Mojolicious

- GraphQL - [Mojolicious::Plugin::GraphQL](https://metacpan.org/pod/Mojolicious::Plugin::GraphQL)
- OpenAPI - [Mojolicious::Plugin::OpenAPI](https://metacpan.org/pod/Mojolicious::Plugin::OpenAPI)

## Languages Integration

- FFI - [FFI::Platypus](https://metacpan.org/pod/FFI::Platypus)

## Language Tooling

- Code coverage metrics - [Devel::Cover](https://metacpan.org/pod/Devel::Cover)
- Code formatter - [perltidy](https://metacpan.org/pod/perltidy)
- Debugger - [perldebug](https://perldoc.perl.org/perldebug)
- Dependencies manager - [Carton](https://metacpan.org/pod/Carton)
- Language server - [Perl::LanguageServer](https://metacpan.org/pod/Perl::LanguageServer), [PLS](https://metacpan.org/pod/PLS)
- Linter - [Perl::Critic](https://metacpan.org/pod/Perl::Critic), [Perl::Critic::Freenode](https://metacpan.org/pod/Perl::Critic::Freenode)
- Moduler installer - [App::cpm](https://metacpan.org/pod/App::cpm) [cpanminus](https://metacpan.org/pod/App::cpanminus)
- REPL - [Reply](https://metacpan.org/dist/Reply/view/bin/reply)
- Version manager - [ASDF](https://github.com/ouest/asdf-perl)

## VS Code

- Code formatter - [Kaktus.perltidy-more](https://marketplace.visualstudio.com/items?itemName=Kaktus.perltidy-more)
- Language server - [richterger.perl](https://marketplace.visualstudio.com/items?itemName=richterger.perl), [FractalBoy.pls](https://marketplace.visualstudio.com/items?itemName=FractalBoy.pls)
- Linter - [d9705996.perl-toolbox](https://marketplace.visualstudio.com/items?itemName=d9705996.perl-toolbox)
- Template highlighting - [kraih.mojolicious](https://marketplace.visualstudio.com/items?itemName=kraih.mojolicious)
