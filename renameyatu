# -*- coding: utf-8 -*-
Plugin.create(:renameyatu) do
command(:renameyatu ,
name: '@t4k3nokoを改名してやる',
condition: lambda{ |opt| true },
visible: true,
role: :postbox)do |opt|

Plugin[:gtk].widgetof(opt.widget).widget_post.buffer.text = "@t4k3nok0 rename "

end
end
