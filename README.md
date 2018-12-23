# signatures
repository for the CBSD 18/19 signature verification project 

the datasets can be found at https://www.math.unipd.it/~nnavarin/Projects/

all the code shoud be compliant with the original folder strucure of the datasets

executions info:

<table>
	<caption>Without preprocessing,HOG = orientations=11, pixels_per_cell=(4,4), cells_per_block=(2,2), image = (70,100)</caption>
        <tr>
		<td>
			class
		</td>
		<td>
			precision
		</td>
                <td>
			recall
		</td>
		<td>
			f1-score
		</td>
                <td>
			support
		</td>
        </tr> 
        <tr>
		<td>
			Genuine Forgery
		</td>
		<td>
			0.66
		</td>
                <td>
			0.64
		</td>
		<td>
			0.65
		</td>
                <td>
			235
		</td>
        </tr>
        <tr>
		<td>
			Genuine Genuine
		</td>
		<td>
			0.66
		</td>
                <td>
			0.68
		</td>
		<td>
			0.67
		</td>
                 <td>
			239
		</td>
        </tr>
        <tr>
		<td>
			Avg
		</td>
		<td>
			0.66
		</td>
                <td>
			0.66
		</td>
		<td>
			0.66
		</td>
                 <td>
			474
		</td>
        </tr>
        <tr>
		<td>
			Execution time
		</td>
		<td>
			0:35:21.516045
		</td>
        </tr>
 <\table>
  
