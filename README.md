opts.plugins = opts.plugins || {};
opts.plugins.legend = {
    display: true,
    position: "left", // Position the legend on the left
    align: "start",   // Align the legend items to the top
    labels: {
        boxWidth: 20, // Width of the legend box
        padding: 10,  // Padding between legend items
        font: {
            size: 12 // Font size for legend labels
        }
    }
};
