# [`jsck`](https://github.com/pandastrike/jsck) - test summary

# All validators fail these tests

some languages do not distinguish between different types of numeric value, a float is not an integer even without fractional part

remote ref, remote ref invalid

fragment within remote ref, remote fragment invalid

ref within remote ref, ref within ref invalid

change resolution scope, changed scope ref invalid

remote ref, remote ref valid

fragment within remote ref, remote fragment valid

ref within remote ref, ref within ref valid

change resolution scope, changed scope ref valid


# [`jsck`](https://github.com/pandastrike/jsck) failed tests

jsck failed the test `valid definition, valid definition schema`. Because the schema failed to load(`Unresolvable $ref values: [&quot;http:&#x2F;&#x2F;json-schema.org&#x2F;draft-04&#x2F;schema#&quot;]`)

jsck failed the test `invalid definition, invalid definition schema`. Because the schema failed to load(`Unresolvable $ref values: [&quot;http:&#x2F;&#x2F;json-schema.org&#x2F;draft-04&#x2F;schema#&quot;]`)

jsck failed the test `maxLength validation, two supplementary Unicode code points is long enough`. Expected result: `true` but validator returned: `false`

jsck failed the test `minLength validation, one supplementary Unicode code point is not long enough`. Expected result: `false` but validator returned: `true`

jsck failed the test `remote ref, containing refs itself, remote ref valid`. Because the schema failed to load(`Unresolvable $ref values: [&quot;http:&#x2F;&#x2F;json-schema.org&#x2F;draft-04&#x2F;schema#&quot;]`)

jsck failed the test `remote ref, containing refs itself, remote ref invalid`. Because the schema failed to load(`Unresolvable $ref values: [&quot;http:&#x2F;&#x2F;json-schema.org&#x2F;draft-04&#x2F;schema#&quot;]`)

jsck failed the test `uniqueItems validation, non-unique array of integers is invalid`. Expected result: `false` but validator returned: `true`

jsck failed the test `uniqueItems validation, numbers are unique if mathematically unequal`. Expected result: `false` but validator returned: `true`

jsck failed the test `uniqueItems validation, non-unique array of objects is invalid`. Expected result: `false` but validator returned: `true`

jsck failed the test `uniqueItems validation, non-unique array of nested objects is invalid`. Expected result: `false` but validator returned: `true`

jsck failed the test `uniqueItems validation, non-unique array of arrays is invalid`. Expected result: `false` but validator returned: `true`

jsck failed the test `uniqueItems validation, non-unique heterogeneous types are invalid`. Expected result: `false` but validator returned: `true`

**All other tests passed**.
