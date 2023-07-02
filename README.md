XML FILE WITH INLINE DTD
<?xml version="1.0"?>
<!DOCTYPE employees [
  <!ELEMENT employees (employee)*>
  <!ELEMENT employee (#PCDATA)>
  <!ENTITY company "Rock and Gravel Company">
]>
<employees>
  <employee>
    Fred Flintstone, &company;
  </employee>
  <employee>
    Barney Rubble, &company;
  </employee>
</employees>
EXPANDED XML 👋 Hi, I’m @sahilsachan-ctrlx
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sahilsachan-ctrlx/sahilsachan-ctrlx is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
