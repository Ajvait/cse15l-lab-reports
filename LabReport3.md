# CSE 15L Lab Report 2 - Adomas Vaitkus

**Part 1:**

Failure-inducing input as a J-Unit Test
```
@Test
  public void failedTest() {
    int[] input1 = {2, 3};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
}
```

Passing input as a J-Unit Test
```
@Test
  public void falsePassTest() {
    int[] input1 = {3, 3};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{3, 3}, input1);
}
```

