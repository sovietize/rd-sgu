svgframes = lifecycle_frames
frame_approval = "00 x approval.png"
frame_refuse = "00 x refuse.png"
frame_report = "00 x report.png"
frame_directory = "00 x directory.png"
frame_title = "00 title_card.png"

# media: approval refuse report directory
frames: title

approval:
	inkscape --export-filename=$(frame_approval) --export-id="Approval" \
	--export-type="png" TApproval.svg
refuse:
	inkscape --export-filename=$(frame_refuse) --export-id="Refuse" \
	--export-type="png" TRefuse.svg
report:
	inkscape --export-filename=$(frame_report) --export-id="Report" \
	--export-type="png" TReport.svg
directory:
	inkscape --export-filename=$(frame_directory) --export-id="Directory-object-class" \
	--export-type="png" TDirectory-object-class.svg

title:
	inkscape --export-filename=$(frame_title) --export-id="title-background" \
	--export-type="png" $(svgframes).svg

clean:
	rm $(frame_approval) $(frame_refuse) $(frame_report) $(frame_directory) \
	$(frame_title)
