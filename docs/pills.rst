Pills
#####

uarray is a library with the ambitious goal of allowing users to write
linear algebra at a high level and translate the math into low level
optimized code for arbitrary heterogeneous distributed
architectures. In order to achieve this goal it is based on a
mathematical theory "Mathematics of Arrays" (MOA) developed by Lenore
Mullin's dissertation. Since then she has published many papers on the
subject and has been actively involved in the direction of
uarray. This material is intended to take a uniformed student and
teach them the fundamentals of MOA. Each "pill" will build upon the
previous one and will be based on lectures that Lenore has given to
the `Quansight <https://www.quansight.com/>`_ team.

MoA - Mathematics of Arrays - defines a formalism (based on APL) to
describe multidimensional arrays and operations on these. On the other
hand, contemporary array processing software (NumPy, Xnd, Apache
Arrow, etc) implement multidimensional array container objects and
define UI to interact with the array objects.

Pill #1
-------

MOA has some fundamental types that we should understand. Additionally
to help with discussion we will be using the following notation.

A **vector** :math:`< 1 2 3 >` is a a one dimensional array.

A **multidimensional array** :math:`[ [ 1 2] [1 2] ]`

You may notice that there is only one type in MOA an array. A vector is only
used to conveniently write operations such as indexing and describing
the shape of an array.

The shape of a multidimensional array is an important concept. It is
identical to thinking of the `shape`. In moa the symbol for shape is
:math:`\rho`.
