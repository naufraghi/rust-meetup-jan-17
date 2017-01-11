# Rust meetup: January, 17

The main idea to focus the effort of this meetup is to produce a proxy application that translates a JSON protocol into a line based, telnet-style protocol.

The telnet server accepts only one connection and it can process only one command at the time. The proxy application, instead, should accept any number of clients and it should multiplex them to the telnet service.
