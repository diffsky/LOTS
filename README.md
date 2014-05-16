# Little Open Ticket System [![](https://travis-ci.org/diffsky/LOTS.png)](https://travis-ci.org/diffsky/LOTS)

**LOTS** is a simple ticketing system for code.

Using twitter style tagging, you can add a `!comment` with a `#tag` and an optional `^priority`. These are then
presented in a web interface. **LOTS** can optionally just find any mention
of the word _TODO_ in your code.

Here is an example of a snippet that would be picked up by **LOTS**:

    ! This readme should be improved #documentation ^2

### Screenshots

#### Tickets

![ticket view](https://raw.githubusercontent.com/diffsky/LOTS/master/public/img/help/tickets.png)

#### File Viewer

![file view](https://raw.githubusercontent.com/diffsky/LOTS/master/public/img/help/file.png)

### Installation

Install lots globally via npm:

    $ [sudo] npm i -g lots

**LOTS** source is [available on github](https://github.com/diffsky/LOTS)

### Usage

In a directory you wish to review your code from, run:

    $ LOTS

Then visit `http://localhost:5000/` to see the report.

See `LOTS -h` for more options


---

Ticket logo designed by [NAS](http://thenounproject.com/nas.ztu) from the [Noun Project](http://thenounproject.com/) :: Creative Commons – Attribution (CC BY 3.0)
