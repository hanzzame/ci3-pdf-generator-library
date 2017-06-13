# Codeigniter PDF Generator
Generate PDF's in CodeIgniter using this easy to use library based on domPDF

# Installation
1. Just drop the Pdf.php and dompdf folder into your libraries directory.

# Usage
$this->load->library('pdf');
$data = array(
	//your data array
);
$filename = "Document_name";
$html = $this->load->view('your_view', $data, TRUE);  
$this->pdf->create($html, $filename);
