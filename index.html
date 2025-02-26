<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <title>BOGO Offer</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://fonts.googleapis.com/css?family=Inter' rel='stylesheet'>
    <style>
        body {
            font-family: 'Inter';
            font-size: 22px;
        }
    </style>
</head>

<body>
    <div class="container">
        <div style="display: flex; align-items: center; gap: 10px;">
            <div style="flex: 1; height: 1px; background-color: gray;"></div>
            <span class="text-bogo">YAY! It's BOGO</span>
            <div style="flex: 1; height: 1px; background-color: gray;"></div>
        </div>

        <div class="offersContainer" id="offersContainer">
            <script>
                const products = [{
                    id: "one",
                    units: "1 Unit",
                    discount: "10% Off",
                    price: "$10.00 USD",
                    originalPrice: "$11.00 USD",
                    sizes: ["S", "M", "L"],
                    colors: ["Black", "White", "Red"]
                },
                {
                    id: "two",
                    units: "2 Unit",
                    discount: "20% Off",
                    price: "$18.00 USD",
                    originalPrice: "$22.50 USD",
                    sizes: ["S", "M", "L"],
                    colors: ["Black", "White", "Red"]
                },
                {
                    id: "three",
                    units: "3 Unit",
                    discount: "25% Off",
                    price: "$25.00 USD",
                    originalPrice: "$30.00 USD",
                    sizes: ["XS", "S", "M", "L"],
                    colors: ["Blue", "Black", "White"]
                },
                ]
                function renderProducts() {
                    const container = document.getElementById("offersContainer");

                    container.innerHTML = products.map(product => `
                            <div class="offer flex-column">
                                <div class="flex-row" style="gap: 12.5px;">
                                    <input type="radio" name="offer" id="${product.id}" value="${product.price}" onchange="toggleGrid('${product.id}')" />
                                    <div class="flex-column" style="flex: 1;">
                                        <div class="flex-row" style="align-items: center;">
                                            <span class="text-unit">${product.units}</span>
                                            <span class="discount text-discount-per">${product.discount}</span>
                                        </div>
                                    </div>

                                    <div style="display: flex; flex-direction: column; justify-content: start;">
                                        <span class="price text-price">${product.price}</span>
                                        <span class="strikethrough text-strick-price">${product.originalPrice}</span>
                                    </div>
                                </div>

                                <div class="grid" id="gridSection${product.id}" style="display: none;">
                                    <span class="label"></span>
                                    <span class="label">Size</span>
                                    <span class="label">Colour</span>

                                    ${Array(2).fill(0).map((_, index) => `
                                        <span class="label">#${index + 1}</span>
                                        <select class="text-selector" style="width: 67px; height: 25px;">
                                            ${product.sizes.map(s => `<option>${s}</option>`).join('')}
                                        </select>
                                        <select class="text-selector" style="width: 72px; height: 25px;">
                                            ${product.colors.map(c => `<option>${c}</option>`).join('')}
                                        </select>
                                    `).join('')}
                                </div>
                            </div>
                        `).join('');
                }

                function toggleGrid(selectedId) {
                    // Hide all grid sections first
                    document.querySelectorAll(".grid").forEach(grid => {
                        grid.style.display = "none";
                    });

                    // Show only the selected grid section
                    const selectedGrid = document.getElementById(`gridSection${selectedId}`);
                    if (selectedGrid) {
                        selectedGrid.style.display = "grid";
                    }
                }

                renderProducts();

            </script>
        </div>


        <div class="flex-row" style="justify-content: space-between;">
            <span class="free-delivery">Free Delivery</span>
            <span class="total">Total : $18.00 USD</span>
        </div>
        <div class="flex-column" style="gap:5px">
            <button onclick="addToCart()">+ Add to Cart</button>
            <span class="flex-row text-discount-per"
                style="font-style: italic; color: gray; justify-content: end; align-items: center;">@ Powered by
                Pumper</span>
        </div>

</body>

</html>
