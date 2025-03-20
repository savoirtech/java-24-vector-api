Performance testing Java 24’s Vector API.

# Test Harness:

JavaVectorAPI-1: <https://github.com/tomerr90/JavaVectorAPI-1.git>

# Test Design:

Using JDK 24 we will run all five test suites from JavaVectorAPI-1 on a
different CPU vendor:

- Intel Xeon E-2378

- AMD Ryzen 9 9950x

- Apple M4 Base

- Qualcomm SnapDragon X Elite X1E80100

# Test Results:

## Intel Xeon E-2378

SimpleSum:

<figure>
<img src="./assets/images/Xeon-SimpleSum.png" alt="SimpleSum" />
</figure>

SimpleSumNoSuperWord:

<figure>
<img src="./assets/images/Xeon-SimpleSumNoSuperWord.png"
alt="SimpleSumNoSuperWord" />
</figure>

ComplexExpression:

<figure>
<img src="./assets/images/Xeon-ComplexExpression.png"
alt="ComplexExpression" />
</figure>

ComplexExpressionNoSuperWord:

<figure>
<img src="./assets/images/Xeon-ComplexExpressionNoSuperWord.png"
alt="ComplexExpressionNoSuperWord" />
</figure>

ArrayStats:

<figure>
<img src="./assets/images/Xeon-ArrayStats.png" alt="ArrayStats" />
</figure>

## AMD Ryzen 9 9950x

SimpleSum:

<figure>
<img src="./assets/images/Ryzen-SimpleSum.png" alt="SimpleSum" />
</figure>

SimpleSumNoSuperWord:

<figure>
<img src="./assets/images/Ryzen-SimpleSumNoSuperWord.png"
alt="SimpleSumNoSuperWord" />
</figure>

ComplexExpression:

<figure>
<img src="./assets/images/Ryzen-ComplexExpression.png"
alt="ComplexExpression" />
</figure>

ComplexExpressionNoSuperWord:

<figure>
<img src="./assets/images/Ryzen-ComplexExpressionNoSuperWord.png"
alt="ComplexExpressionNoSuperWord" />
</figure>

ArrayStats:

<figure>
<img src="./assets/images/Ryzen-ArrayStats.png" alt="ArrayStats" />
</figure>

## Apple M4 Base

SimpleSum:

<figure>
<img src="./assets/images/Apple-SimpleSum.png" alt="SimpleSum" />
</figure>

SimpleSumNoSuperWord:

<figure>
<img src="./assets/images/Apple-SimpleSumNoSuperWord.png"
alt="SimpleSumNoSuperWord" />
</figure>

ComplexExpression:

<figure>
<img src="./assets/images/Apple-ComplexExpression.png"
alt="ComplexExpression" />
</figure>

ComplexExpressionNoSuperWord:

<figure>
<img src="./assets/images/Apple-ComplexExpressionNoSuperWord.png"
alt="ComplexExpressionNoSuperWord" />
</figure>

ArrayStats:

<figure>
<img src="./assets/images/Apple-ArrayStats.png" alt="ArrayStats" />
</figure>

## Qualcomm SnapDragon X Elite X1E80100

SimpleSum:

<figure>
<img src="./assets/images/SnapDragon-ArrayStats.png" alt="SimpleSum" />
</figure>

SimpleSumNoSuperWord:

<figure>
<img src="./assets/images/SnapDragon-SimpleSumNoSuperWord.png"
alt="SimpleSumNoSuperWord" />
</figure>

ComplexExpression:

<figure>
<img src="./assets/images/SnapDragon-ComplexExpression.png"
alt="ComplexExpression" />
</figure>

ComplexExpressionNoSuperWord:

<figure>
<img src="./assets/images/SnapDragon-ComplexExpressionNoSuperWord.png"
alt="ComplexExpressionNoSuperWord" />
</figure>

ArrayStats:

<figure>
<img src="./assets/images/SnapDragon-ArrayStats.png" alt="ArrayStats" />
</figure>

# Test Analysis:
