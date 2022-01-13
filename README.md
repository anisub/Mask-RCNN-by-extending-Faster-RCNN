# CIS 581 Final Project: Mask RCNN
-- Anirudh Subramanyam and Hari Santhanam

Code Submission Structure:

-- 9 files
-- codebase: Python 3

- Mask RCNN: (main folder)
	-- Main Files:
		-- final_project_boxhead_maskhead_cis680.ipynb
		-- final_project_rpn_cis680.ipynb

	-- Support Files and helpers:
		-- backbone.py
		-- BoxHead.py
		-- dataset.py
		-- MaskHead.py
		-- rpn.py
		-- utils.py
		-- pretrained_models.py

-- Instructions to run:

1. Upload the main Mask RCNN folder to google colab with a folder called 'data' storing the required COCO data.
2. This implementation runs the Region Proposal Network(RPN) separately from the Box and Mask head networks
3. Train the RPN first and use the trained weights to run the Box and Mask head
4. Connect to GPU instance and 'run all'
5. Training and Inference is performed in the notebook
6. To run Box and Mask head, change path to saved rpn weights from RPN run, connect to gpu instance and 'run all'
7. Training and Inference is performed in the notebook