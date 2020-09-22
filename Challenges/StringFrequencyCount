# Problem description
# Write a program that counts frequency of each letter in the string (string consists lowercase letters only).

[String]$sampleString = "use this string as the sample text"
$occurances = New-Object System.Collections.Hashtable

# for every occurance of a character in the string, increment a value for that character in a hashtable
for ($i = 0; $i -lt $sampleString.Length; $i++) { $occurances[$sampleString.Substring($i,1)]++ }
# display and sort the hashtable by name
$occurances.GetEnumerator() | Sort-Object -Property Name