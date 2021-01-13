# image-resize
image resize


```php

      $this->load->library('image_lib');  
			$config1['image_library'] = 'gd2';
			$config1['source_image'] = $fPath; 
			//$config1['create_thumb'] = TRUE; 
			$config1['maintain_ratio'] = TRUE;
			$config1['width']         = 320;     
			$config1['height']       = 320;  

			$this->image_lib->initialize( $config1);  
			$this->image_lib->resize(); 
			$this->image_lib->clear(); 

```
