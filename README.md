 # 🚀 Excited to share my latest project using Next.js!
I developed a that includes multiple sections like Header, Hero, About Us, Portfolio, and Footer. Each section is styled using Tailwind CSS, ensuring a clean and modern design.

# 💡 Key highlights of the project:

Header: A clean, centered header with easy navigation.
Hero Section: A hero section with a call-to-action button for further exploration.
About Us: Simple yet effective about section with personal info.
Portfolio: Displays my latest assignments with interactive buttons for detailed viewing.
Footer: A footer for smooth navigation and a unified design.

# 📂 Code Snippet:
Here’s a small peek into the core structure using Next.js and Tailwind CSS:

```
const Home = () => {
  return (
    <head>
      <body className="font-sans bg-gray-100">

     {/* Header */}
     <header className="bg-blue-600 text-white py-6">
      <a href="/header"><h1 className="text-4xl font-bold container mx-auto text-center">Header </h1></a>
     </header>

     {/* Hero Section */}
     <section className="bg-gray-50 py-20">
<h2 className="text-5xl font-bold text-gray-800 container mx-auto text-center"> Hero Section</h2>
<p className="mt-4 text-gray-600 conatiner text-center">This is Hero Section of the Page</p>
<a href="/button"><button className="mt-6 bg-blue-500 text-white px-6 py-3 mx-auto grid place-content-center text-center rounded-lg hover:bg-blue-400">Details</button></a>
     </section>

{/* About Section  */}
<section className="bg-white py-20 container mx-5 text-center">
  <h2 className="text-4xl font-bold text-gray-800">About Us</h2>
  <p className="mt-4 text-gray-600">Created by Ali Zaid</p>
</section>

{/* Portfolio Section  */}
<section className="bg-gray-50 py-20 container mx-auto text-center">
  <h2 className="text-4xl font-bold text-gray-800">These are my latest assignments</h2>
  <div className="grid grid-cois-1 md:grid-cois-2 lg:grid-cois-3 gap-8 mt-8">

{/* Portfolio Assignmants  */}
<div className=" bg-white p-6 shadow-lg "><a href="/assignment">
<div><button className="mt-6 bg-blue-500 text-white px-6 py-3 mx-auto grid place-content-center text-center rounded-lg hover:bg-blue-400">Assignment 1</button></div></a>
<a href="/assignment"><div><button className="mt-6 bg-blue-500 text-white px-6 py-3 mx-auto grid place-content-center text-center rounded-lg hover:bg-blue-400">Assignment 2</button></div></a>
 </div></div>
</section>

{/* Footer  */}
<footer className="bg-blue-600 text-4xl text-white py-6 container mx-auto text-center">
 <a href="/footer"><p>Footer</p></a>
</footer>
  </body>
    </head>
  )
}

export default Home
```


