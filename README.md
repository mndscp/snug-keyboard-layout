# Snug

Snug is an alternate keyboard layout optimized for increased typing comfort and speed in both English and German. The goal was to have as few SFBs as possible while also keeping redirects low and rolls high.

SFB stands for **Same Finger Bigram**. Two keys are called an SFB if you have to use the same finger for typing the two letters in sequence. On QWERTY for example, `de`/`ed` are SFBs. You want as few SFBs as possible to increase typing comfort and speed. The word `follow` has four letters all typed with one finger which is neither comfortable nor fast.

**Redirects** are made up of three keys and your fingers kind of change direction when typing them. They are not very pleasant to type so you want to avoid these as well during layout creation. QWERTY examples: `sad`, `you`, `lip`.

**Rolls** are comfortable sequences of keys that are all typed with different fingers, going one direction on your hand, like `wet`, `hop`, and `awe`.

Find scores of all these factors compared to other layouts in the analysis section.

## The layout

Options for different keyboard types

### Matrix or ortholinear

```
q l d m b  y f o u '
s r t c g  p n e i a
z x k w v  j h / , .
```

### Row-stagger

```
q l d m b y f o u '
 s r t c g p n e i a
  z x k w v j h / , .
```

## Angle mod

The **angle mod** tries to make typing on the quite asymmetricly designed row-stagger keyboard layout more comfortable for the left hand. With how the rows of the keyboard are all slanted to the left even though your hands are symmetric you move your left hand in a way that can cause ulnar deviation which is not healthy. The theoretical solution is to change which finger you use for the five lower left keys.

On traditional row-stagger the keys are `z x c v b` typed with fingers `5 4 3 2 2` where `5` is your pinky and `2` your index finger. With the angle mod you shift each finger over to the left by one key. The keys and fingers change this way: Type `x c v b z` with fingers `4 3 2 2 2`.

### Row-stagger with angle mod on ANSI keyboard

```
q l d m b y f o u '
 s r t c g p n e i a
  x k w v z j h / , .
```

### Row-stagger with angle mod on ISO keyboard

```
q l d m b y f o u '
 s r t c g p n e i a
z x k w v   j h / , .
```
If you have an additional key left of the `z` key like on ISO keyboards you can simply shift over the whole left row don't have to reach far for the former `b` key anymore. You can bind that to something else that you use less often. After getting used to the angle mod it should decrease typing fatigue on your left hand. It takes some getting used to but you should give it a try and then decide what you like better. The angle mod works on row-stagger keyboards independently of the typing layout you use.
