# Allergies

**Intern should*...*  
given a person's allergy *score*(of type `int`), determine whether or not they are allergic to a given item, and their full list of allergies.

Each bit of the score is associated with one of the allergies. Each allergy is an item of an enum type called *Allergen*.

The last paragraph of page 127 of our book, talks about how common/sufficient it is to use an `int` value as a collection of enum items! intern can review that part.

Intern should pay attention that the numbers associated with enum items, each just have one bit set! (one of the bits is 1 and all other bits are 0). This is what the book calls **mutually exclusive** choices!

## Notes

- `Enum.HasFlag` can be used!
- bit operations can be used as alternative to `HasFlag`.
- `Enum` type could be made more familiar through this exercise.
