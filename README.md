# Codeigniter PDF Generator
Generate PDF's in CodeIgniter using this easy to use library based on domPDF

# Installation
1. Just drop the Pdf.php and dompdf folder into your libraries directory.

# Usage
```
$this->load->library('pdf'); // or pdf_ssl for ssl only
$data = array(
	//your data array
);
$filename = "Document_name";
$html = $this->load->view('your_view', $data, TRUE);`  
$this->pdf->create($html, $filename);
```

# Help
For more information on how to use domPDF then please visit: [https://github.com/dompdf/dompdf/wiki/Usage](https://github.com/dompdf/dompdf/wiki/Usage)

# License
* CodeIgniter PDF Library - MIT License
* domPDF - GNU Lesser GPL

# Credits
* [domPDF](https://github.com/dompdf) 
