# Codeigniter PDF Generator
Generate PDF's in CodeIgniter using this easy to use library based on domPDF

# Requirements
* Codeigniter 3.x.x
* PHP version 5.3.0 or higher

# Easy Installation
* Just copy files in libraries folder into your libraries directory.

# Usage
```
//load library
$this->load->library('pdf'); // change to pdf_ssl for ssl
$filename = "Document_name";
$html = $this->load->view('your_view_template');
$this->pdf->create($html, $filename);
```

You can also pass in data to the function just as you would using
```
$html = $this->load->view('your_view_template', $data, TRUE);
```

# Help
For more information on how to use domPDF then please visit: [https://github.com/dompdf/dompdf/wiki/Usage](https://github.com/dompdf/dompdf/wiki/Usage)

# License
* CodeIgniter PDF Library - MIT License
* domPDF - GNU Lesser GPL

# Credits
* [domPDF](https://github.com/dompdf) 
