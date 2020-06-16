# Navyblue.BaseLibrary
A library for basic usage, like ToJson, FromJson&lt;> and other extensions for int, long, DateTime, Byte, Dictionary, Enum, Guid, MD5 and soon.

This library is not just a extension tool, but also aims to make your code is more like OOP pattern.

# Samples (string)
- Convert Json Format String to Object
```
Object obj = jsonString.FromJson<Object>();
```

- Convert Object to Json Format String
```
string jsonString = obj.ToJson();
```
- IsNullOrEmpty
```
if(str.IsNullOrEmpty())
{
    // your code
}
```
# Samples (int)
- 3.IsBetween(2, 5);// return true
- Loop
```
  3.Times().Do(p =>
  {
      Console.WriteLine("Hello world");
  });
```
# Samples (GUID)
```
- Guid.NewGuid().ToGuidString();
- "XXXXXXXXXXXXXXXXXXXXX".ToGuid()
```
```
- //Creates a sequential GUID according to SQL Server's ordering rules.
- GuidUtility.NewSequentialGuid()
```
# Samples (MD5)
```
- MD5Hash.ComputeMD5Hash("111111111"); // return byte[]
- MD5Hash.ComputeMD5HashString("111111111"); return string 
```
# Samples (Byte)
```
- byteObj.ASCII();
- byteObj.GetBytesOfASCII();
- byteObj.Unicode();
- byteObj.GetBytesOfUnicode();
- byteObj.Utf8();
- byteObj.GetBytesOfUTF8();
......
```
# Samples (DateTime)
```
- dateTimeObj.DurationToNow();
- dateTimeObj.IsAfter(destination);
- dateTimeObj.IsAfterOrEqual(destination);
- dateTimeObj.IsBefore(destination);
- dateTimeObj.IsBefore(destination);
......
```
# Samples (IEnumerable)
```
- iEnumerableObj.ForEach(Action);
- iEnumerableObj.GetLength();
- iEnumerableObj.GetPage();
- iEnumerableObj.IsNotNullOrEmpty();
- iEnumerableObj.Join(destination);
- iEnumerableObj.IsEnumerableEmpty();
- iEnumerableObj.IsSequenceNullOrEmpty();
......
```
# ***Also, there are many other extension functions for you. Last but note least, please give me a star, many thanks***
