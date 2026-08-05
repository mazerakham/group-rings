# Origin

I did not set out to make a problem set. I set out to kill an evening.

For a while I had been going back and forth with Claude, sometimes in the browser and
sometimes in the terminal, about a thing I did not have the right name for. I had written
down the multiplication rule for what I was calling `D_8[R]` and `Q_8[R]`, worked it out by
hand for both, and then generalized it. I was reasonably sure I had derived something real.
I was not sure it had a name, and I was not sure I had the notation the right way around.

It has a name. They are **group rings**, the notation is `R[G]` with the coefficients on the
outside, and the general multiplication formula I had derived is convolution. That was the
first useful thing I learned that night, and it cost me one sentence to find out.

I had the dihedral subscript wrong too, or at least non-standard. I was writing `D_8` for the
symmetries of the square, which is what Dummit & Foote does, indexing by order. Most everyone
else indexes by the polygon: `D_n` has order `2n`, so the square is `D_4` and `D_3` is `S_3`.
The set uses the polygon convention throughout. The irritating consequence is that `D_4` and
`Q_8` both have order 8 while looking like they should not, and there is no fixing that.

So I asked for problems. Elementary ones, the kind at the front of a chapter, testing
definitions and basic manipulation, with enough hand computation that I would actually have
to hold the multiplication table in my head. That is sections A through D.

Then it kept going, because I kept asking.

I remembered there had been some claim about eigenvalues, and it occurred to me that left
multiplication by a fixed element is a linear transformation, so it has a spectrum, and I
wanted to know whether that spectrum was ever interesting. It is. It is the regular
representation, and for a cyclic group it is literally the discrete Fourier transform.
Sections E and F.

Then I wanted the isomorphism `C[D_4] = C[Q_8]` built by hand, with hints thin enough that
solving it would still be worth something. Section I.

Then I wanted the group determinant, which I did not know existed, and which turns out to be
the thing that explains why the *real* group algebras of `D_4` and `Q_8` differ: two
quadratic forms in four variables, differing by two signs. Section H. Euler's four-square
identity falls out of it, which I did not see coming.

Then I asked to be shown something I could not have dreamed of proving before learning what
a group ring is. That is section K: quadratic reciprocity, obtained by writing down one
element of a group ring, squaring it, and reducing it modulo a second prime.

Then I said the corridor I actually wanted was group rings to algebra to manifolds and
harmonics, and that is section L. It ends at spherical harmonics, which turn out to be the
same theorem as `C[D_4] = C^4 x M_2(C)`, only compact.

Fifty-four problems. Answers are collapsed. There is a button at the bottom of the page if
you want them all at once.

Two notes for anyone else reading it.

**First**, the notational trap in problem 16 cost me real time before it was written down,
and it will cost you time too if you skip it. The element of `Q_8` that everybody writes as
`-1` is not the ring element `-1`. Writing it as `z` fixes the problem permanently.

**Second**, none of this is original. It is a standard first pass through a standard subject.
What is unusual is the route: it was assembled in one sitting, in the order I happened to get
curious, which is not the order a textbook would choose. I think that is a feature. Having
the group determinant show up before the isomorphism it explains is backwards pedagogically
and exactly right motivationally.

---

*Drafted by Claude at my direction, in one session, on 5 August 2026. The curiosity and the
sequencing are mine. The prose and every computation are its. I have not checked every line.*

— Jake Mirra
