
<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
@prefix : <urn:solid:mpc#>.

:sources a :MPCSourceSpec;
  :source :src1, :src2.

:src1 a :MPCSource;
  :pref <https://uri/to/reference1>;
  :data <https://uri/to/data1>.

:src2 a :MPCSource;
  :pref <https://uri/to/preference2>;
  :data <https://uri/to/data2>.
```
