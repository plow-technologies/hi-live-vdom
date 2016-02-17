
module Main where
import           Control.Concurrent.STM.Notify
import qualified Data.Sequence                 as S
import           LiveVDom
import           $moduleName

main :: IO ()
main = do
--  mapM_ addCss cssFiles
--   mapM_ addJs jsFiles
  container <- createContainer
  runDom container (return ()) $$ hello
