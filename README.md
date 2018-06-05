# convplex
Verilog implementation of a convolution complex.

## Verilog HDL

### Modules
```
module ModuleName #(
    parameter para = x,  // comments
    //...
)(
    input wire input_name,
    //...

    output [para-1:0] output_name,
    //...
);

    // statements

endmodule
```
### Sequential signals naming convention

* clock, posedge triggered: `clk`
* clock, negedge triggered: `clk_n`
* enable, active high: `en`
* reset, active high: `rst`
