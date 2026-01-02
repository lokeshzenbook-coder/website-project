fetch("http://localhost:5000/api/products")
  .then(res => res.json())
  .then(data => {
    const productsDiv = document.getElementById("products");
    if (!productsDiv) return;

    data.forEach(p => {
      const div = document.createElement("div");
      div.innerHTML = `<h3>${p.name}</h3><p>$${p.price}</p>`;
      productsDiv.appendChild(div);
    });
  });
