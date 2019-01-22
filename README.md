This is an interactive web page intended to help you understand your U.S. taxes.

You're viewing the source repository; try the graph itself at https://b-k.github.io/1040.js/ .

You might use this utility to answer questions like:

* What is the overall flow from income statements to the final refund?

* If my tax situation changes, like buying a house or having a kid, how does the shape of my taxes change?

* People keep telling me that having an IRA will reduce my tax bill. By how much?

* If I had a million dollars, what would my taxes look like? What would they look like
if I made it all in capital gains?

* My mom/dad/libertarian friend complains about how taxes are overwhelmingly complicated, but I don't
think they're so crazy difficult. How can I walk them through the process?

* A lawmaker has proposed changing tax law, like a flat tax or changing the mortgage
interest deduction to a mortgage interest credit. How can I get an idea of what those
changes would look like?

* If you have cloned a copy of the repository, you can rebuild with the version tagged `2017` and do
a side-to-side comparison of how taxes worked before and after the reform in December 2017.

On privacy
========

The web page is completely standalone. All the math happens in your browser; no data
is sent to any server.


Doing your taxes
========

If your sole interest is to "do" your taxes, you may prefer to use the Python project
that uses the cell database from 1040.js to produce output that looks more like your
tax form, at https://github.com/b-k/py1040 .

You can also file directly with the IRS using FFFF [ https://www.freefilefillableforms.com ].
IRS form 1040 was first developed in 1913, and largely retains the same organization
as the original. Technically, it does not hide intermediate steps from the user, but
it is hard to argue that its layout of a long list of lines, many of which refer to
lines on other forms, makes the flow at all clear.

FFFF is written, but at best partially maintained, by Intuit, and leaves the user to
do some calculations him or herself. So it can be productive to check your math
using this tax graph or py1040, then use the results to fill in the missing calculations
at FFFF.


Caveats
========

The tax graph on this form is incomplete. For example, the earned income credit
calculation is in place, but if you are a member of the clergy there is a different
calculation. There are some details for people making over $155,000/year (AGI) which we
will handle if any of the contributors ever have that problem. The code is open source,
and you are encouraged to add cells or logical nuances that apply to your situation;
see Contributing.md for details.

Citing it
========
Here is some information for citing this project in an academic setting:

> Author = Ben Klemens
>
> Title = 1040.js
>
> DOI = 10.5281/zenodo.1054109
>
> year = 2017

The author does work at the US Treasury's Office of Tax Analysis, but because this is an unofficial release in no way officially reviewed by Treasury, please do not list an author affiliation.
